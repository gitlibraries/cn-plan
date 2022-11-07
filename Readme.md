# Readme

## Dockerd configure example

```json
{
    "registry-mirrors": [
        "https://xxxx.com"
    ],
    "dns": ["8.8.8.8"]
}
```

## Vcpkg configure example (Ubuntu 20.04)

```bash
echo "export X_VCPKG_ASSET_SOURCES="`curl -L https://raw.githubusercontent.com/cloudlibraries/cn-plan/master/vcpkg` >> ~/.bashrc && source ~/.bashrc
```

## Hosts example
来源<https://raw.hellogithub.com/hosts>
```bash
curl -L https://raw.githubusercontent.com/cloudlibraries/cn-plan/master/hosts >> /etc/hosts
```

## Sources.list example

```bash
curl -L https://raw.githubusercontent.com/cloudlibraries/cn-plan/master/ubuntu-20.04-sources.list >> /etc/apt/sources.list
```