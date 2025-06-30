# Symmetric Encryption & Cryptography 

A Java EE web application demonstrating symmetric-key encryption. The application provides a JSP-based form and a servlet filter to encrypt user input before display.

---

## 🚀 Quickstart

1. **Import** the `encryption_CLI` project in your IDE or place the `Code/encryption_CLI` folder in your servlet container’s webapps directory.
2. **Configure** your encryption settings in `Code/encryption_CLI/private/private.properties`.
3. **Build & Deploy**:
   - Use your IDE’s build and deploy tools, or
   - Package as WAR and drop into a servlet container (Tomcat, Jetty).
4. **Access** the app at `http://localhost:8080/encryption_CLI/`.
5. **Submit** text via the form; encrypted output will appear on the response page.

---

## 🧩 Project Structure

```
Code/
└── encryption_CLI/
    ├── encryption_CLI.iml         
    ├── .idea/                     
    ├── lib/                       
    ├── private/                   
    │   ├── private.properties     
    │   └── private.xml            
    └── src/
        ├── conf/                  
        │   └── MANIFEST.MF        
        ├── java/encryptor/       
        │   ├── encrypt_filter.java  
        │   └── EncryptFilter.java   
        └── web/
            ├── index.jsp          
            ├── Response.jsp       
            └── WEB-INF/
                └── web.xml        
```

---

## 🔧 Prerequisites

- **Java JDK 8+**  
- **Java EE servlet container** (Tomcat 8+, Jetty)  
- **Jpcap library** dependencies (if live capture enabled)

---

## 🔒 Security Notes

- **Protect** the `private/` directory; exclude from version control.  
- Use strong, random keys of correct length for chosen algorithm.  
- For production, consider injecting secrets via environment or vault.

---

## 🚀 License

This project is released under the **MIT License**. See `LICENSE` for details.

---

## 📬 Contact

For questions or feedback, contact **kothakonda.baby@gmail.com**.
