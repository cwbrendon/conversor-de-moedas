# 💱 Conversor de Moedas

Aplicativo mobile para conversão de moedas em tempo real, desenvolvido com React Native e Expo.

---

## 📱 Funcionalidades

- Conversão em tempo real entre 8 moedas internacionais
- Inversão rápida entre moeda de origem e destino
- Taxa de câmbio atualizada via API externa
- Interface limpa e responsiva

---

## 🌍 Moedas Suportadas

| Símbolo | Moeda |
|--------|-------|
| 🇺🇸 USD | Dólar Americano |
| 🇧🇷 BRL | Real Brasileiro |
| 🇪🇺 EUR | Euro |
| 🇬🇧 GBP | Libra Esterlina |
| 🇯🇵 JPY | Iene Japonês |
| 🇨🇦 CAD | Dólar Canadense |
| 🇦🇺 AUD | Dólar Australiano |
| 🇨🇭 CHF | Franco Suíço |

---

## 🛠️ Tecnologias

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [ExchangeRate API](https://www.exchangerate-api.com/)

---

## 🚀 Como rodar localmente

**Pré-requisitos:** Node.js e Expo Go instalado no celular

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/conversor-de-moedas.git

# Acesse a pasta
cd conversor-de-moedas

# Instale as dependências
npm install

# Inicie o projeto
npx expo start
```

Escaneie o QR Code com o aplicativo **Expo Go** (Android) ou com a câmera (iOS).

---

## 📂 Estrutura do Projeto

```
src/
├── components/
│   ├── Button/
│   ├── Input/
│   └── ResultCard/
├── constants/
│   └── Currencies.js
├── services/
│   └── api.js
├── styles/
│   └── Colors.js
└── utils/
    └── convertCurrency.js
```

---

## 👨‍💻 Autor

Feito com 💙 por **[Brendon](https://github.com/cwbrendon)**
