# Executor Python Internal

Executor Python avançado, totalmente **independente do Python instalado no sistema**, com suporte a:

- **Python internal** (versão 3.10.10) incluída no pacote  
- **Syntax Highlight profissional** usando Pygments  
- **Autocomplete inteligente** usando Jedi (análise de escopo avançada)  
- **Terminal integrado** bloqueado para escrita (apenas saída)  
- **Botão "Rodar Código"** para executar scripts Python diretamente  
- **Temas visuais**: VSCode Dark e Dracula  
- **Compatível com Windows** e distribuído com instalador NSIS

---

## 📦 Estrutura do projeto

ExecutorPython/
├─ executor.py # Código principal do Executor
├─ pythontudo/ # Python internal (3.10.10)
│ ├─ python.exe
│ └─ Lib/
│ └─ tkinter/ # Inclui ttk e outros módulos
├─ icon.ico # Ícone opcional do EXE
├─ installer.nsi # Script do instalador NSIS
└─ README.md



---

## ⚙️ Requisitos

- Windows 10 ou superior  
- Nenhum Python externo necessário, pois **Python internal já está incluído**  
- NSIS (apenas se quiser criar o instalador)

---

## 🚀 Instalação (usuário final)

1. Execute o **instalador gerado pelo NSIS**:
2. Escolha a pasta de instalação (por padrão `C:\Program Files\ExecutorPython`)  
3. O instalador cria também **um atalho na área de trabalho**

4. Abra o Executor pelo atalho.  

---

