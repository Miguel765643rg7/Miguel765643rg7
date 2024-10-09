<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Planejamento de Saúde e Bem-Estar</title>
</head>
<body>
    <h1>Formulário de Planejamento de Saúde e Bem-Estar</h1>
    <form action="https://formspree.io/f/[seu-endereco]" method="POST">
        <label for="name">Nome Completo:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        
        <label for="email">E-mail:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        
        <label for="objetivo">Objetivo de Saúde e Bem-Estar:</label><br>
        <textarea id="objetivo" name="objetivo" rows="4" cols="50" required></textarea><br><br>
        
        <label for="prazo">Prazo para Alcançar o Objetivo:</label><br>
        <input type="date" id="prazo" name="prazo" required><br><br>
        
        <label for="dificuldades">Quais as dificuldades enfrentadas?</label><br>
        <textarea id="dificuldades" name="dificuldades" rows="4" cols="50"></textarea><br><br>
        
        <input type="submit" value="Enviar">
    </form>
</body>
</html>
