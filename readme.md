Salt box
============

### Set up
* Add 'config.yaml' to the root directory if you would like to keep your Digital Ocean tokens private:

```yaml
---
configs:
    use: 'staging'
    staging:
        token: ''
    production:
        token: ''
```
* Install vagrant [Digital Ocean provider] (https://github.com/smdahlen/vagrant-digitalocean/)
* Push to Digital Ocean using:
        $ vagrant up --provider=digital_ocean
