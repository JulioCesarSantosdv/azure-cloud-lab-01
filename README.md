# Azure Cloud Lab 01

Laboratório técnico em Azure com foco em infraestrutura, 
segurança e FinOps — do provisionamento ao desprovisionamento.

---

## Objetivos

- Foundation reutilizável com Resource Groups, VNet e NSG
- Workload real: Windows Server Core + IIS com HTTP e HTTPS
- Troubleshooting em camadas (serviço, porta, NSG, conectividade)
- Ciclo de vida controlado com desprovisionamento e registro de custos

---

## Escopo

| Item         | Valor                             |
|--------------|-----------------------------------|
| Região       | Brazil South                      |
| Nomenclatura | Microsoft CAF                     |
| SO           | Windows Server 2022 (Server Core) |
| Workload     | IIS — HTTP/80 e HTTPS/443         |
| Acesso admin | RDP restrito por IP (/32)         |
| Custo real   | R$ 20,74                          |

---

## Arquitetura

Foundation: VNet, subnets segmentadas, NSG com deny by default  
Workload: VM, NIC, Public IP, OS Disk — Resource Group dedicado

---

## Status

| Fase                | Status                      |
|---------------------|-----------------------------|
| Auditoria e FinOps  | Concluída                   |
| Foundation          | Concluída                   |
| LAB 01 — Web Server | Concluído e desprovisionado |
| LAB 02 — Monitoring | Pendente                    |
| LAB 03 — Backup     | Pendente                    |

---

## Documentação

A documentação técnica completa com evidências, decisões 
arquiteturais, incidentes e análise de custos está disponível em:  
[azure-cloud-lab-01.pdf](docs/azure-cloud-lab-01.pdf)

---

Autor: Julio Cesar Santos  
LinkedIn: linkedin.com/in/juliocesarsantos
