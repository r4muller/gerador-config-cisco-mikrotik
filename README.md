# Gerador de configuração · Cisco & MikroTik

# Gerador de configuração · Cisco & MikroTik

Ferramenta web para gerar scripts de configuração de **Cisco IOS / IOS XE** e **MikroTik RouterOS** a partir de uma interface visual.


## Funcionalidades

- Seletor de plataforma: Cisco ou MikroTik
- Mapeamento visual de portas (WAN, WAN 2, tronco, acesso, livre)
- VLANs com DHCP, gateway, helper e políticas
- WAN: DHCP, IP fixo ou PPPoE + failover
- Segurança: firewall, restrição de gestão, usuários, SSH
- Cisco: STP, LACP, OSPF, ACLs, AAA, IP SLA, Port Security, DHCP Snooping/DAI
- MikroTik: bridge com VLAN filtering, FastTrack, isolate/shared
- Validação com erros e avisos
- Tema claro/escuro automático
- 100% client-side (sem backend)

## Como usar

1. Abra `gerador-cisco-mikrotik.html` no navegador  
   *(ou acesse a [versão online via GitHub Pages](#))*
2. Escolha **Cisco IOS / XE** ou **MikroTik RouterOS**
3. Configure equipamento, portas, VLANs e WAN
4. Copie o script gerado e aplique no equipamento

## Tecnologias

- HTML5, CSS3 e JavaScript (vanilla)
- Sem dependências de build ou frameworks
- Persistência local via `localStorage`

## Estrutura
****
