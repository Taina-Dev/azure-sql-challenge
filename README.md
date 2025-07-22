# azure-sql-challenge
Desafio Prático: Instância de Banco de Dados no Azure

# 🚀 Desafio Prático: Instância de Banco de Dados no Azure

Este repositório reúne minha experiência prática no desafio de **configurar uma instância de Banco de Dados SQL gerenciado no Azure**, como parte do curso da DIO.

---

## 🎯 Objetivos do Desafio

- **Aplicar conhecimentos** sobre provisionamento de SQL no Azure  
- **Documentar processos** técnicos de forma clara e estruturada  
- **Utilizar GitHub** para compartilhar documentação e artefatos  

---

## ✅ O que eu fiz

1. **Assistir a todas as vídeo-aulas** sem pular nenhuma etapa.  
2. **Provisionamento da Instância SQL**  
   - Criada uma instância **Azure SQL Managed Instance** na região “Sul do Brasil”.  
   - Definido nível de serviço e DTUs/vCores conforme orientação.  
3. **Configuração de Rede e Segurança**  
   - Ajustadas regras de firewall para permitir meu IP de desenvolvimento.  
   - Habilitado o acesso seguro via Azure Private Link (opcional).  
4. **Testes de Conectividade**  
   - Conectei ao banco usando **SQL Server Management Studio** e **Azure Data Studio**.  
   - Executei scripts de criação de tabelas e inserção de dados (veja `/scripts`).  
5. **Documentação e Evidências**  
   - Adicionei capturas de tela das etapas em `/images`.  
   - Organizei observações técnicas e boas práticas no texto abaixo.

---

## 📷 Capturas de Tela

| Etapa                     | Imagem                                            |
|---------------------------|---------------------------------------------------|
| Configuração de firewall  | ![Firewall](images/configuracao-firewall.png)   |
     

---

## 🔧 Observações Técnicas

- **SKU e Nível de Serviço**: usei `General Purpose` com 2 vCores para testes iniciais.  
- **Segurança**: configurei firewall permitindo apenas meu IP fixo.  
- **Scripts SQL**: estão na pasta `/scripts` para demonstração de criação de esquema e dados.  
- **Custos**: lembre-se de parar ou excluir a instância após os testes para evitar cobranças.

---

## 📚 Recursos Úteis

- [Criar Instância Gerenciada de SQL do Azure (MS Learn)](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/quickstart-create-managed-instance)  
- [Documentação Azure SQL Firewall](https://learn.microsoft.com/pt-br/azure/azure-sql/database/firewall-configure)  

---

## ✍️ Autor

Desafio concluído por Tainá Corrêa
Bootcamp Microsoft Azure – DIO.me  

