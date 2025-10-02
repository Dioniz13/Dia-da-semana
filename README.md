# 📅 Verificador de Dia da Semana

Um programa simples em JavaScript que pergunta ao usuário o dia da semana e retorna uma mensagem de cumprimento apropriada.

## ✨ Funcionalidades

- Interface interativa com o usuário
- Validação de entrada de dados
- Mensagens personalizadas para dias úteis e fim de semana
- Execução direta no navegador

## 🚀 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/verificador-dia-semana.git

2.  Abra o arquivo index.html no seu navegador

Ou execute diretamente criando um arquivo HTML:
<!DOCTYPE html>
<html>
<head>
    <title>Verificador de Dia da Semana</title>
</head>
<body>
    <script>
        let diaDaSemana = prompt('Qual o dia da semana?');
        if (diaDaSemana == 'domingo' || diaDaSemana == 'sábado') {
            alert(`Hoje é ${diaDaSemana}. Bom fim de semana!`);
        }
        else if (diaDaSemana == 'segunda' || diaDaSemana == 'terça' || diaDaSemana == 'quarta' || diaDaSemana == 'quinta' || diaDaSemana == 'sexta') {
            alert(`Hoje é ${diaDaSemana}. Boa semana!`);
        }
        else {
            alert('Dia inválido!');
        }
    </script>
</body>
</html>

💻 Código
let diaDaSemana = prompt('Qual o dia da semana?');
if (diaDaSemana == 'domingo' || diaDaSemana == 'sábado') {
    alert(`Hoje é ${diaDaSemana}. Bom fim de semana!`);
}
else if (diaDaSemana == 'segunda' || diaDaSemana == 'terça' || diaDaSemana == 'quarta' || diaDaSemana == 'quinta' || diaDaSemana == 'sexta') {
    alert(`Hoje é ${diaDaSemana}. Boa semana!`);
}
else {
    alert('Dia inválido!');
}

🎯 Exemplos de Funcionamento
Entrada: "segunda" → Saída: "Hoje é segunda. Boa semana!"

Entrada: "sábado" → Saída: "Hoje é sábado. Bom fim de semana!"

Entrada: "domingo" → Saída: "Hoje é domingo. Bom fim de semana!"

Entrada: "quarta" → Saída: "Hoje é quarta. Boa semana!"

Entrada: "invalidoday" → Saída: "Dia inválido!"

📋 Dias Válidos
Dias úteis: segunda, terça, quarta, quinta, sexta

Fim de semana: sábado, domingo

🛠️ Tecnologias Utilizadas
HTML5

JavaScript Vanilla

Prompt e Alert do navegador

📁 Estrutura do Projeto
verificador-dia-semana/
│
├── index.html          # Arquivo principal
├── script.js           # Arquivo JavaScript 
└── README.md           # Documentação

🤝 Contribuindo
Contribuições são bem-vindas! Para contribuir:

Faça um Fork do projeto

Crie uma Branch para sua feature (git checkout -b feature/AmazingFeature)

Commit suas mudanças (git commit -m 'Add some AmazingFeature')

Push para a Branch (git push origin feature/AmazingFeature)

Abra um Pull Request

📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

⭐ Se este projeto foi útil, deixe uma estrela no repositório!
