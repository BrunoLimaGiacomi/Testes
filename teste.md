# Security Policy

Este documento define como a segurança é tratada neste projeto/repositório e fornece os canais adequados para reportar problemas, incidentes ou dúvidas relacionadas à segurança.  

---

## 📖 Documentações de Segurança e Arquitetura

- [Arquitetura de Segurança da informação](https://gerdaucld.sharepoint.com/sites/PortaldeSegurancaDaInformacao/SitePages/ArchSec/Documentation.aspx?stay=true)  
- [Checklist de Revisão de Segurança](https://gerdaucld.sharepoint.com/sites/PortaldeSegurancaDaInformacao/SitePages/ArchSec/Security-Assessment-Questions.aspx)  

---

## 🚨 Reporte de Vulnerabilidades e Incidentes

Se você identificar uma vulnerabilidade ou suspeitar de um incidente de segurança:

1. Entre em contato pelos seguintes canais:  
   - E-mail: [InformationSecurity@gerdau.com](mailto:InformationSecurity@gerdau.com)  
   - Ao enviar um email, descreva o ocorrido com máximo de detalhes, não esquecendo da data/hora do ocorrido e dos usuários que foram impactados ou que possam ser impactados.


**Tempo de resposta esperado:**  
- Confirmação do recebimento: até **12h úteis**  
- Análise inicial e classificação: até **24h úteis**  

---


## 🛡️ Security Champion

Cada repositório/projeto possui um responsável de segurança ("Security Champion"):  

- **Nome:** João Silva  
- **E-mail/Contato:** [joao.silva@empresa.com](mailto:joao.silva@empresa.com)  
- **Substituto:** Maria Oliveira (em caso de ausência)  

---

## 🔒 Práticas de Segurança do Projeto

- Uso de **SAST ORCA** automatizado em CI/CD  
- Varredura de dependências com **[SCA do Orca]**  
- [Revisões de falsos positivos](https://gerdau.service-now.com/gerdau?id=sc_cat_item&sys_id=983c7e1e874f121094ba62430cbb35c6)  
- Gerenciamento de segredos via **[Vault Hashicorp](https://gerdaucld.sharepoint.com/sites/PortaldeSegurancaDaInformacao/SitePages/ArchSec/IAM/Procedimento_Para_Gerar_Segredos_Com_AppRoles_No_Vault_Hashicorp.aspx?stay=true)** (nunca commit em repositório)  
- Logs centralizados e monitorados por **[Datadog]**  

## 📅 Última Atualização

Este documento foi atualizado em: **22/10/2025**