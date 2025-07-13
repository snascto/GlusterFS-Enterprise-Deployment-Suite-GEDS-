
# GlusterFS Enterprise Deployment Suite (GEDS)

## Pré-requisitos

- Ubuntu 22.04 LTS
- 8+ cores CPU
- 16GB+ RAM
- 2+ discos disponíveis
- Conectividade 10Gbps recomendada

## Instalação Rápida


wget https://raw.githubusercontent.com/santo-nascimento/geds/main/src/geds.sh
chmod +x geds.sh
sudo ./geds.sh


## Uso


# Modo interativo (recomendado)
sudo ./geds.sh

# Modo automático (para implantações em massa)
sudo ./geds.sh --auto --config cluster-config.json


## Configuração

Edite o arquivo `config.ini` antes da execução:


[network]
bonding_mode = 802.3ad
vlan_id = 100

[storage]
auto_config = true
filesystem = xfs

## Contribuição

1. Faça um fork do projeto
2. Crie sua branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## Contato

Santo Nascimento - sammm59a@gmail.com

[![GitHub issues](https://img.shields.io/github/issues/santo-nascimento/geds)](https://github.com/santo-nascimento/geds/issues)
