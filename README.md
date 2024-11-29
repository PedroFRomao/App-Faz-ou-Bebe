# Faz ou Bebe - Mobile App

**Bem-vindo ao Faz ou Bebe!**  
Este é um aplicativo mobile inspirado no famoso jogo de festa que combina diversão e desafios. Ideal para quebrar o gelo ou animar qualquer reunião de amigos!  

## 🎮 O que é o jogo Faz ou Bebe?  
Faz ou Bebe é um jogo simples e divertido, perfeito para momentos de descontração.  

### Como jogar:  
1. **Sorteie um desafio:** o jogador toca na tela, e um desafio é sorteado automaticamente.  
2. **Cumprir ou beber:** o jogador pode escolher realizar o desafio ou recusar.  
   - Se aceitar, ele realiza o desafio e passa para o próximo jogador.  
   - Se recusar, deve beber um shot ou gole e acumula um ponto de penalidade.  
3. **Declare o vencedor:** ao final do jogo, quem tiver menos pontos será o vencedor!  

O aplicativo oferece:  
- **Desafios variados** que vão do engraçado ao ousado.  
- **Interface simples e acessível**, ideal para festas e eventos.  

---

## 📱 Funcionalidades do App  
- 🎲 **Desafios aleatórios**: diversão garantida com desafios que mantêm a imprevisibilidade.  
- 🔄 **Navegação intuitiva**: fácil de usar para todos os jogadores.  
- 🌐 **Sem necessidade de internet**: jogue em qualquer lugar, a qualquer momento!  

---

## 🚀 Tecnologias Utilizadas  
- **Flutter**: framework moderno para o desenvolvimento mobile.  
- **Dart**: linguagem principal para garantir desempenho e flexibilidade.  

---

## 🌟 Objetivo do Projeto  
Este aplicativo foi criado como parte do meu aprendizado em **Flutter** e desenvolvimento de aplicativos móveis. Meu objetivo é:  
- Praticar a criação de interfaces modernas e interativas.  
- Aprender a estruturar um projeto mobile completo.  
- Explorar a implementação de lógica de jogo e funcionalidades offline.  

---

## 🔮 Ideias Futuras  
Estou trabalhando para adicionar mais recursos e tornar o app ainda mais divertido e personalizável. Algumas ideias incluem:  
- **Desafios customizados:** permita que os jogadores criem seus próprios desafios exclusivos.  
- **Vários modos de jogo:** adicione modos temáticos, como *Hardcore* ou *Desafios Rápidos*.  
- **Multilíngue:** suporte em Inglês, tornando o app acessível para mais pessoas.  

Essas melhorias estão planejadas para versões futuras do aplicativo. Fique de olho para mais novidades!  

## 📂 Estrutura do Projeto  

# Exemplos.  

### Diretórios principais:  
- **lib/**: contém o código principal do aplicativo Flutter.  
  - **pages/**: telas do aplicativo (ex.: página inicial, jogo, configurações).  
  - **widgets/**: componentes reutilizáveis (botões, cards de desafio, etc.).  
  - **services/**: lógica de integração com o banco de dados e API.  
- **assets/**: imagens, ícones e outros recursos.  
- **database/**: scripts para criar e gerenciar o banco de dados MySQL.  

---

## 🔧 Como executar o projeto  

### Clone o repositório:  

```bash
git clone https://github.com/seuusuario/faz-ou-bebe.git  
cd faz-ou-bebe  
```

### Instale as dependências:

```bash
flutter pub get
```

### Execute o aplicativo:

```bash
flutter run
```

## 🛠️ Funcionalidades no Código

### Geração de desafios aleatórios

Localizado em **lib/services/challenge_service.dart.**

```dart
Copiar código
Future<String> getRandomChallenge() async {
  // Conecta ao banco de dados e retorna um desafio aleatório.
  return "Exemplo de desafio aleatório"; // Modifique para a implementação real.
}
```

### Interface de Jogo

Localizado em **lib/pages/game_page.dart.**

```dart
Copiar código
class GamePage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: Text('Faz ou Bebe')),
      body: ChallengeDisplay(), // Widget de exemplo.
    );
  }
}
```
