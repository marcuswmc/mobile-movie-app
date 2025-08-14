# 🎬 Mobile Movie App

Um aplicativo mobile moderno para descoberta e gerenciamento de filmes, desenvolvido com **Expo** e **React Native**.

## 📱 Sobre o Projeto

O **Mobile Movie App** é uma aplicação multiplataforma que permite aos usuários:
- 🔍 Pesquisar filmes
- 💾 Salvar filmes favoritos
- 👤 Gerenciar perfil de usuário
- 📺 Visualizar detalhes dos filmes

## 🛠️ Tecnologias Utilizadas

- **Expo** - Framework para desenvolvimento React Native
- **React Native** - Framework para desenvolvimento mobile
- **TypeScript** - Linguagem de programação tipada
- **NativeWind** - Framework CSS para React Native
- **Tailwind CSS** - Framework de utilitários CSS
- **Expo Router** - Sistema de roteamento baseado em arquivos
- **React Navigation** - Navegação entre telas

## 🚀 Como Executar

### Pré-requisitos

- Node.js (versão 18 ou superior)
- npm ou yarn
- Expo CLI
- Android Studio (para Android) ou Xcode (para iOS)

### Instalação

1. **Clone o repositório**
   ```bash
   git clone [URL_DO_REPOSITORIO]
   cd mobile-movie-app
   ```

2. **Instale as dependências**
   ```bash
   npm install
   ```

3. **Inicie o projeto**
   ```bash
   npm start
   # ou
   npx expo start
   ```

### Opções de Execução

Após executar `npm start`, você terá as seguintes opções:

- **Expo Go**: Escaneie o QR code com o app Expo Go no seu dispositivo
- **Android Emulator**: Pressione `a` para abrir no emulador Android
- **iOS Simulator**: Pressione `i` para abrir no simulador iOS (apenas macOS)
- **Web**: Pressione `w` para abrir no navegador

## 📁 Estrutura do Projeto

```
mobile-movie-app/
├── app/                    # Páginas da aplicação (Expo Router)
│   ├── (tabs)/            # Navegação por abas
│   │   ├── index.tsx      # Tela inicial
│   │   ├── search.tsx     # Tela de pesquisa
│   │   ├── saved.tsx      # Tela de filmes salvos
│   │   └── profile.tsx    # Tela de perfil
│   ├── movies/            # Páginas de filmes
│   │   └── [id].tsx       # Detalhes do filme
│   └── _layout.tsx        # Layout principal
├── assets/                # Recursos estáticos
│   ├── icons/            # Ícones da aplicação
│   ├── images/           # Imagens e backgrounds
│   └── fonts/            # Fontes personalizadas
├── constants/            # Constantes e configurações
├── interfaces/           # Definições de tipos TypeScript
└── types/               # Tipos adicionais
```

## 🎨 Design System

O projeto utiliza um sistema de cores personalizado:

- **Primary**: `#030014` - Cor principal escura
- **Secondary**: `#151312` - Cor secundária
- **Accent**: `#AB8BFF` - Cor de destaque
- **Light**: Tons claros para textos e elementos
- **Dark**: Tons escuros para backgrounds

## 📱 Funcionalidades

### ✅ Implementadas
- [x] Estrutura base do projeto
- [x] Navegação por abas
- [x] Sistema de roteamento
- [x] Configuração de estilos com NativeWind
- [x] Definição de interfaces TypeScript

### 🚧 Em Desenvolvimento
- [ ] Integração com API de filmes
- [ ] Interface de pesquisa
- [ ] Sistema de favoritos
- [ ] Perfil de usuário
- [ ] Detalhes dos filmes

## 🔧 Scripts Disponíveis

```bash
npm start          # Inicia o servidor de desenvolvimento
npm run android    # Executa no emulador Android
npm run ios        # Executa no simulador iOS
npm run web        # Executa no navegador
npm run lint       # Executa o linter
```

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🤝 Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📞 Suporte

Se você encontrar algum problema ou tiver dúvidas, abra uma [issue](https://github.com/seu-usuario/mobile-movie-app/issues) no repositório.

---

Desenvolvido com ❤️ usando Expo e React Native
