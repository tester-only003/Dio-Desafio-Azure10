# Ferramentas de Gerenciamento e Implantação Azure

## Ferramentas de implantação de recursos
- Portal, PowerShell, CLI e outras
- Azure Arc e Azure Resource Manager

### Objetivos:
- Descrever o portal do Azure
- Descrever o Azure Cloud Shell, incluindo a CLI do Azure e o Azure PowerShell.
- Descrever a finalidade do Azure Arc.
- Descrever o ARM (Azure Resource Manager) e modelos do ARM do Azure.
<br>

   <div align="center">
   <img width="561" height="172" alt="FErramentas-Implatacao-1" src="https://github.com/user-attachments/assets/f935eca1-09c3-4dac-bc24-56228a8f8d9e" />
   </div>
<br>

> [!NOTE] 
> * ***NOTA:  o que diferencia o Azure Cloud Shell ou o CLI é a familiaridade de uso com os comandos em ambiente Windows ou Linux.
[!NOTE]

<br>

### Azure Arc
- Ferramenta nos moldes do MultCloud.

   <div align="center">
   <img width="703" height="305" alt="Azure-Arc-1" src="https://github.com/user-attachments/assets/1b9b5ab4-e7f3-4fe6-bed9-b96cb089ab02" />
   </div>
<br>

- Serve para fazer o gerenciamento dos recursos que não estão dentro do Azure.
    - ***Os recursos que estão dentro Azure não são gerenciados pelo ARC, somente os que estão fora.***
    - Pode, por exemplo, gerenciar máquinas virtuais que estão na AWS ou no GCP.
    - (outro exemplo) É possível gerenciar uma VM que está na AWS e aplicar políticas que são nativas da Microsoft.
<br>

   <div align="center">
    Painel do Arc <br>
    <img width="489" height="394" alt="Painel-Arc-1" src="https://github.com/user-attachments/assets/0be38502-f6fe-49f9-ab5b-bde229ad056e" />
   </div>
<br>


### ARM (Azure Resource Manager)
Fornece uma camada de gerenciamento que permite criar, atualizar e excluir recursos da assinatura do Azure.
<br>

   <div align="center">
    <img width="526" height="372" alt="ARM-1" src="https://github.com/user-attachments/assets/65497b95-341c-4795-9e60-f77c501c7647" />
   <br>
     *** O ARM recebe as requisições, e a partir daí ele vai administrar os recursos, criando o que foi solicitado.
   </div>
<br>

#### Infraestrutura como código
- Garanta consistência na implantação em todo o ecossistema de nuvem.
- Gerencie a configuração em escala.
- Provisione rapidamente ambientes adicionais com base em uma configuração e um build padrão.

<br> 

### Modelos do ARM (Azure Resource Manager)
Os modelos do ARM são arquivos JSON (JavaScript Object Notation) que podem ser usados para criar e implantar a infraestrutura do Azure sem a necessidade de escrever comandos de programação.
<br>

- Sintaxe declarativa
- Resultados repetíveis
- Orquestração
- Arquivos modulares
- Validação Integrada
- Código exportável
<br>

   <div align="center">
    <img width="483" height="317" alt="Modelo_ARM-1" src="https://github.com/user-attachments/assets/7bc1271c-dc68-431c-b135-b3d081a252d7" />
   </div>
<br>

### Azure Bicep
- Linguagem nativa Microsoft.
- Compatível apenas com a nuvem da Microsoft (não são aceitos em outras nuvens).
<br>

   <div align="center">
    <img width="513" height="345" alt="Azure-Bicep-1" src="https://github.com/user-attachments/assets/9432a6cd-44e1-4b58-bb8a-620bf75e87a6" />
   </div>
<br>

### Bicep Playground
Ferramenta para comparar a sintaxe do Bicep e do modelo em ARM (Azure Resource Manager): [https://azure.github.io/bicep/](https://azure.github.io/bicep/) <br>
  > [!NOTE] 
  > * Recurso usado para automações (para criar recursos em lotes).
  [!NOTE]
  <br>

  <div align="center">
  Console Bicep Playground <br>
  (No lado esquerdo o modelo em Bicep e do lado direito o modelo em ARM) <br>
  <img width="743" height="370" alt="Bicep-Playground-1" src="https://github.com/user-attachments/assets/9f38e7de-2454-47bb-9903-814d0e663488" />
  </div>
<br>

### Links para estudar

[https://learn.microsoft.com/training/modules/describe-features-tools-manage-deploy-azure-resources/1-introduction](https://learn.microsoft.com/training/modules/describe-features-tools-manage-deploy-azure-resources/1-introduction)

[https://learn.microsoft.com/training/modules/describe-features-tools-manage-deploy-azure-resources/3-describe-purpose-of-azure-arc](https://learn.microsoft.com/training/modules/describe-features-tools-manage-deploy-azure-resources/3-describe-purpose-of-azure-arc)

[https://learn.microsoft.com/en-us/devops/deliver/what-is-infrastructure-as-code#deploy-iac-on-azure](https://learn.microsoft.com/en-us/devops/deliver/what-is-infrastructure-as-code#deploy-iac-on-azure)






