# srp_energy

_Due to [ADR0004](https://github.com/home-assistant/architecture/blob/master/adr/0004-webscraping.md) this integration was removed from [Home Assistant](https://github.com/home-assistant/home-assistant/tree/0.99.0) with version 0.100, and are now republished here._

⚠️ This integration scrapes a website to get the information!
⚠️ There are no one actively maintaining this repository.

The `srp_energy` integration shows information from Srp hourly energy usage report for their customers. The srpenergy module fetches the data found on the website.

You need a Username, Password, and AccountId which you can create at [Srp](https://www.srpnet.com).

## Example configuration.yaml

```yaml
sensor:
  - platform: srp_energy
    username: YOUR_USERNAME
    password: YOUR_PASSWORD
    id: YOUR_ACCOUNT_ID
```

### Configuration options

Key | Type | Required | Description
-- | -- | -- | --
`username` | `string` | `True` | Your username for SRP.
`password` | `string` | `True` | Your password for SRP.
`binary_sensor` | `list` | `True` | Your account id for SRP.