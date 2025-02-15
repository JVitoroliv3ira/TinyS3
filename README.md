# **TinyS3 - S3 Local para Desenvolvimento 🚀**  

**TinyS3** é um **servidor local de armazenamento compatível com AWS S3**, desenvolvido para facilitar testes e desenvolvimento sem precisar de um serviço externo. Ele fornece os principais **endpoints e funcionalidades essenciais** do S3, permitindo que desenvolvedores simulem integrações locais com SDKs da AWS.  

⚠ **Este projeto está em desenvolvimento.**  

---

## **📌 Principais Features (Planejadas para o MVP)**
✅ Criar, listar e deletar **buckets**  
✅ Upload, download e remoção de **objetos**  
✅ Listagem de objetos dentro de um bucket  
✅ Suporte a **presigned URLs** para acessos temporários  
✅ Upload Multipart para arquivos grandes  
✅ Suporte a **metadados (`x-amz-meta-*`)**  
✅ Rodável facilmente via **Docker**  

---

## **📍 Roadmap do MVP**
### **🔹 Fase 1 - Funcionalidades Essenciais**
✅ Criar, listar e deletar **buckets**  
✅ Upload e download de **objetos**  
✅ Listagem de **objetos em um bucket**  
✅ Suporte a **metadados (`x-amz-meta-*`)**  
✅ API rodando localmente via **FastAPI**  

### **🔹 Fase 2 - Melhorias e Compatibilidade**
🔄 Suporte a **presigned URLs**  
🔄 Implementação de **upload multipart**  
🔄 Melhorias na autenticação com **API Key opcional**  
🔄 Suporte a **filtros (`prefix`, `delimiter`)** na listagem de objetos  

### **🔹 Fase 3 - Expansão e Refinamento**
🔲 Suporte a **AWS Signature v4** (para compatibilidade total com SDKs)  
🔲 Simulação de **Storage Classes (STANDARD, GLACIER)**  
🔲 UI Web para visualização de arquivos (opcional)  
🔲 Melhorias de performance e otimização  

---

## **💡 Contribuindo**
Este projeto ainda está em **desenvolvimento**. Se quiser contribuir, abra um **Pull Request** ou reporte um bug via **Issues**.  

---

## **📜 Licença**
TinyS3 é um projeto **open-source** e está licenciado sob a **GPL v3**.
