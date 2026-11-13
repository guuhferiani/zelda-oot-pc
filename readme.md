<div align="center">

# 🗡️ Hookshot: The Legend of Zelda: Ocarina of Time (PC Nativo)

**Ocarina of Time (Nintendo Switch 2) rodando nativamente no Windows e Linux, sem emulador.**

---

</div>

## 📖 Sobre o Projeto

O **Hookshot** é um projeto de **recompilação estática**. O código do jogo original de Switch 2 é traduzido diretamente para C++ nativo e compilado em um executável de computador (`hookshot.exe`). 

- **Sem camada de emulação pesada:** O jogo roda com desempenho nativo de PC.
- **Gráficos em Vulkan:** Renderizador moderno de alta performance reconstruído do zero.
- **Tecnologias Modernas:** Suporte nativo a **NVIDIA DLSS (com DLAA)**, **AMD FSR 4**, **Frame Generation** e monitores **Ultrawide (21:9)**.
- **Totalmente Local:** A compilação é feita na sua própria máquina usando o seu dump legítimo do jogo.

---

> [!IMPORTANT]
> **Aviso de Preservação e Direitos Autorais:**  
> Este repositório **não contém código protegido por direitos autorais, jogos, chaves (keys) ou arquivos proprietários da Nintendo**. Todo o conteúdo executável e assets são gerados localmente no computador do usuário a partir da sua cópia legítima (`.nup` / v131072).

---

## 💻 Requisitos do Sistema

- **Processador:** Intel Core i5/i7 (10ª geração ou superior) ou AMD Ryzen 3000/5000+
- **Memória RAM:** 16 GB recomendado (ou mínimo 12 GB)
- **Placa de Vídeo:** Compatível com **Vulkan 1.3** e **Mesh Shaders**
  - **NVIDIA:** GeForce RTX série 20, 30 ou 40
  - **AMD:** Radeon RX série 6000 ou 7000
  - **Intel:** Linha Arc A-Series
- **Sistema Operacional:** Windows 10/11 64-bit ou Linux x86_64

---

## 🚀 Como Compilar e Jogar no Windows

1. Baixe o instalador oficial: [`HookshotBuilder.exe`](https://github.com/guuhferiani/zelda-oot-pc/releases/latest).
2. Execute o **HookshotBuilder.exe**.
3. Selecione o seu arquivo do jogo do Switch 2 (`.nup`, versão v131072 / `0400486024DEC000`).
4. Ative os recursos recomendados para sua placa de vídeo:
   - Se sua GPU for **NVIDIA RTX**: Marque **NVIDIA DLSS**.
   - Se sua GPU for **AMD Radeon**: Marque **AMD FSR 4**.
   - Mantenha marcada a opção **Prepare shaders now** (para evitar travadinhas no jogo).
5. Clique em **Build the game**. O processo leva entre 10 e 20 minutos.
6. Quando a barra chegar em 100%, clique em **Play** ou use o atalho gerado na Área de Trabalho!

---

## 🎮 Menu de Configurações no Jogo

Durante o jogo, você pode pressionar a tecla **`F1`** ou **`Insert`** para abrir o menu suspenso de configurações:

- **Upscaler:** Escolha entre **DLSS**, **FSR** ou resolução nativa.
- **Geração de Quadros (Frame Generation):** Multiplicador de FPS suave para monitores de alta taxa de atualização (144Hz+).
- **Modo Ultrawide:** Expande o campo de visão da câmera para preencher telas 21:9 sem distorcer o Link.
- **Velocidade de Texto:** Opção de acelerar diálogos e mensagens na tela.
- **Mapeamento de Controles:** Suporte nativo a controles de Xbox, PlayStation, Switch Pro Controller e teclado/mouse.

---

*Projeto desenvolvido pela comunidade para fins educacionais e de preservação histórica de software.*
