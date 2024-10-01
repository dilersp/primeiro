# Projeto Incrível
Este é um projeto fictício para ensinar conceitos de *Git*, *GitHub* e *Markdown*. Ele simula um sistema de gerenciamento de tarefas, onde os usuários podem criar, editar e excluir tarefas. O foco principal deste projeto é demonstrar as melhores práticas de uso do *Git* e como criar uma boa documentação com o arquivo `README.md`. :tada:

## Funcionalidades
- [x] Criar novas tarefas
- [x] Editar tarefas existentes
- [x] Excluir tarefas
- [ ] Enviar lembretes por email (~~em desenvolvimento~~)

## Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-incrivel.git
   ```

2. Acesse o diretório do projeto:
   ```bash
   cd projeto-incrivel
   ```

3. Instale as dependências:#
   ```bash
   pip install -r requirements.txt
   ```

## Uso
Após a instalação, você pode rodar o sistema localmente usando o seguinte comando:

```bash
python main.py
```

<details><summary>Exemplo de uso:</summary>

```bash
python main.py --nova-tarefa "Estudar Git e Markdown"
```

Isso irá criar uma nova tarefa com o título "Estudar Git e Markdown".
</details>

## Estrutura do Projeto
```bash
.
├── README.md
├── main.py
├── tarefas/
│   ├── criar.py
│   ├── editar.py
│   └── excluir.py
└── tests/
    ├── test_criar.py
    ├── test_editar.py
    └── test_excluir.py
```

## Contribuição
1. Faça um fork do projeto 
2. Crie um branch com a feature que deseja implementar
   ```bash
   git checkout -b minha-nova-feature
   ```
3. Faça o Commit de suas mudanças
   ```bash
   git commit -m "Adiciona nova feature"
   ```
4. Faça o push para a branch
   ```bash
   git push origin minha-nova-feature
   ```
5. Abra um Pull Request
   
## Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.  

## Contato
Caso tenha dúvidas, entre em contato através de:
- [LinkedIn](https://linkedin.com/in/dilermando-piva-jr-4373a765/)
- [Email](mailto:pivajr@gmail.com)

## Tecnologias Utilizadas
[![Python](https://img.shields.io/badge/python-3.8-blue)](https://python.org)
![Flask](https://img.shields.io/badge/flask-2.0-green)

## Tabela de Exemplos

| Funcionalidade    | Status      |
|-------------------|-------------|
| Criar tarefas     | Completo    |
| Editar tarefas    | Completo    |
| Excluir tarefas   | Completo    |
| Enviar lembretes  | Em progresso|  


---  

>> "A documentação é tão importante quanto o código!"  
> - Desenvolvedor Sábio


## Referências
1. [Documentação Oficial do Git](https://git-scm.com/doc)
2. [Documentação do GitHub](https://docs.github.com/en)

[Site oficial do Python][1]

[1]: https://python.org


