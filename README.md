# Smash Burguer - Landing Page & Painel Administrativo

## 🍔 Sobre o Projeto
Este projeto é uma **landing page para a hamburgueria Smash Burguer**, localizada em Medianeira - PR.  
Ele inclui:

- **Landing Page (index.html):** Mostra os produtos, horários, avaliações, contato e botão para WhatsApp com mensagem automática.
- **Painel Administrativo (admin.html):** Permite adicionar, editar e remover produtos, incluindo imagens diretamente da galeria.  
- **Integração local:** Os produtos são salvos no `localStorage` do navegador, permitindo atualização instantânea na página principal.

O site foi construído usando **HTML, CSS e JavaScript puro**, sem dependências externas.

---

## 📁 Estrutura de Arquivos


---

## ⚙️ Funcionalidades

### Landing Page
- Exibe os produtos cadastrados no painel.
- Botão para WhatsApp com **mensagem automática**.
- Sessões:
  - Hero/banner com destaque.
  - Produtos com imagens, nome, descrição e preço.
  - Horários de atendimento, com indicação "Aberto Agora" ou "Fechado".
  - Contato (telefone e Instagram).
  - Avaliações de clientes.

### Painel Administrativo
- Login protegido por senha (padrão: `admin123`).
- Adicionar/editar/excluir produtos.
- Upload de imagens da galeria (armazenadas em Base64 no `localStorage`).
- Botão para abrir a **Landing Page** em outra aba.
- Botão para apagar todos os produtos, se necessário.

---

## 🔧 Como Usar

### 1. Abrir o site localmente
- Coloque os arquivos em uma pasta.
- Abra `index.html` no navegador para visualizar a landing page.
- Abra `admin.html` para acessar o painel.

### 2. Painel Administrativo
1. Digite a senha (`` ou a sua personalizada).
2. Adicione produtos com:
   - Nome
   - Descrição
   - Preço
   - Imagem (opcional)
3. Clique em **Adicionar / Atualizar**.
4. Produtos aparecem automaticamente na landing page.

### 3. Botão WhatsApp
- Configurar o número real no link do botão:
```htm
