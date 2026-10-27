# Software As A Service Infrastructure: Biblioteca

| Campo      | Informação                                                                 |
|------------|----------------------------------------------------------------------------|
| **Data**   | 10/2026                                                                    |
| **Status** | Aceito                                                                     |
| **Autor**  | Melissa Sequeira — [mehsequeiracampos@gmail.com](mehsequeiracampos@gmail.com)| 
|            | Brunno Borges Ferri — [brunnoborgesf@gmail.com](brunnoborgesf@gmail.com)   |
|            | Vinicius Fernandes — [viniartshowcase2gmail.com](viniartshowcase@gmail.com)|                                                                         |

---

## Contexto

Uma infraestrutura de uma biblioteca onde seria possivel armazenar seus livros alugados para fins de estudo.

## Decisão

Optou-se pelo seguinte conjunto de software:

- **Virtualização:** VMware Workstation 17
- **Sistema operacional:** Linux, Ubuntu Server 26.04 LTS
- **Banco de dados:** MySQL 8.4.10
- **Servidor de aplicação:** Apache Tomcat 10
- **Ferramentas adicionais:** utilitários de apoio usadas em aula e distribuídas por outros meios

A integração proposta serve a dois propósitos: **acesso e manutenção** e **estudo**.
Na branch da máquina virtual está incluída a VM com Ubuntu Server 26.04 LTS, MySQL 8.4.10 e as ferramentas complementares.

### Credenciais (ambiente de estudo)

> ⚠️ **Atenção:** as credenciais abaixo são apenas para fins didáticos. Não há segurança aplicada no momento. **Não utilize em produção.**

| Serviço          | Usuário | Senha |
|------------------|---------|-------|
| Acesso na VM     | `saas`  | `saas` |
| Servidor Tomcat  | `admin` | `saas` |
| MySQL            | `saas`  | `saas` |
| ...              |         |       |

### Acesso remoto

O MySQL está liberado para acesso remoto, mas essa configuração pode variar conforme o ambiente.

## Consequências

O utilizador pode adotar a infraestrutura como base, migrá-la e adaptá-la para onde for necessário.
