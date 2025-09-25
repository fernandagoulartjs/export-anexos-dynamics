# Exportação de Anexos - Dynamics CRM
Ferramenta em **C# (.NET Framework)** para exportação de anexos de incidentes no Microsoft Dynamics CRM 2013/2016.  
O objetivo é facilitar a extração massiva de arquivos anexados, organizando-os de forma prática para análise ou backup.

---

## ✨ Funcionalidades
- Exporta anexos relacionados a entidades de incidentes.
- Permite configuração do período de exportação via `App.config`.
- Suporte a grandes volumes de dados.
- Geração de logs de execução.

---

## ⚙️ Requisitos
- .NET Framework 4.x  
- Microsoft Dynamics CRM SDK  
- Acesso ao banco de dados ou serviço do CRM  

---

## 🚀 Como usar
1. Configure a conexão e parâmetros no arquivo **`App.config`**:
   - Data inicial (`start`)
   - Pasta de destino
   - Conexão com o CRM
2. Compile e execute o console.  
3. Os anexos serão exportados para o diretório definido.

---

## 📂 Estrutura do Projeto
- `Program.cs` → Lógica principal do console  
- `App.config` → Configuração de parâmetros  
- `Logs/` → Saída de logs  

---

# Attachment Export - Dynamics CRM
Tool in **C# (.NET Framework)** to export attachments from incidents in Microsoft Dynamics CRM 2013/2016.  
The goal is to facilitate bulk extraction of attached files, organizing them in a practical way for analysis or backup.

---

## ✨ Features
- Exports attachments related to incident entities.
- Configurable export period via `App.config`.
- Supports large data volumes.
- Execution log generation.

---

## ⚙️ Requirements
- .NET Framework 4.x  
- Microsoft Dynamics CRM SDK  
- Database or CRM service access  

---

## 🚀 How to use
1. Set up connection and parameters in **`App.config`**:
   - Start date (`start`)
   - Output folder
   - CRM connection
2. Build and run the console.  
3. Attachments will be exported to the defined directory.

---

## 📂 Project Structure
- `Program.cs` → Main console logic  
- `App.config` → Parameters configuration  
- `Logs/` → Execution output logs  

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).
