
# Projeto Clínica Médica

O **Projeto Clínica Médica** é uma aplicação web desenvolvida para o gerenciamento de consultas médicas. O sistema permite o cadastro de médicos, gerenciamento de agendamentos e exibição das consultas de forma prática e acessível. Utilizando tecnologias modernas e uma estrutura modular, o projeto é ideal para clínicas de pequeno e médio porte que buscam digitalizar seus processos.

---

## Tecnologias Utilizadas

### Front-end
- **HTML/CSS**: Estruturação e estilização da interface.
- **JavaScript**: Funcionalidades interativas e manipulação de DOM.

### Back-end
- **JSON Server**: Utilizado como banco de dados local para simulação de persistência de dados e criação de uma API REST.

### Outras Ferramentas
- **Vite**: Ferramenta de build para desenvolvimento rápido.
- **Node.js**: Gerenciamento de dependências e execução de scripts.
- **Git/GitHub**: Controle de versão e repositório remoto.

---

## Recursos do Projeto

- **Cadastro de Médicos**: Interface para registrar informações sobre os médicos da clínica.
- **Agendamento de Consultas**: Ferramenta para criar, visualizar e gerenciar agendamentos.
- **Gerenciamento de Consultas**: Exibição de consultas agendadas, com filtros por data e médico.
- **Simulação de API REST**: Uso do JSON Server para fornecer uma API local com suporte para GET, POST, PUT e DELETE.

---

## Configuração do Ambiente de Desenvolvimento

### Pré-requisitos
Certifique-se de que o Node.js e o npm estão instalados em sua máquina.

### Passo a Passo

1. **Clone o Repositório**:
   ```bash
   git clone <URL_DO_REPOSITÓRIO>
   cd Clinica-Medica-main
   ```

2. **Instale as Dependências**:
   ```bash
   npm install
   ```

3. **Inicie o JSON Server**:
   ```bash
   npx json-server --watch db.json --port 3000
   ```

4. **Execute o Servidor de Desenvolvimento**:
   ```bash
   npm run dev
   ```

5. **Acesse a Aplicação**:
   - Abra `http://localhost:5173` no navegador.

---

## Estrutura do Projeto

- **`index.html`**: Página inicial do projeto.
- **`db.json`**: Banco de dados local utilizado pelo JSON Server.
- **`package.json`**: Contém informações sobre o projeto e suas dependências.
- **`vite.config.js`**: Arquivo de configuração do Vite.
- **Pasta `dist/`**: Contém os arquivos gerados após a build da aplicação.
- **Pasta `.github/workflows/`**: Configurações de workflows para integração contínua (CI).

---

## Como Contribuir

1. Faça um fork do repositório.
2. Crie uma nova branch para suas alterações:
   ```bash
   git checkout -b feature/minha-alteracao
   ```
3. Commit suas alterações:
   ```bash
   git commit -m "Descrição da alteração"
   ```
4. Envie para o repositório remoto:
   ```bash
   git push origin feature/minha-alteracao
   ```
5. Abra um Pull Request no repositório original.

---

## Imagens do Projeto

Adicione capturas de tela que demonstrem:
- Tela inicial.
- Interface de cadastro de médicos.
- Visualização de consultas agendadas.

---

## Licença

Este projeto está sob a licença [MIT](LICENSE). Sinta-se à vontade para usá-lo e modificá-lo conforme necessário.

---

Essa documentação pode ser expandida conforme novas funcionalidades ou melhorias sejam implementadas.
