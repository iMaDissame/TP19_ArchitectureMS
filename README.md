# Microservices — Tests & Endpoints

---

## 🟦 Eureka Server  
**Registered services visible:**
- GATEWAY  
- SERVICE-CLIENT  
- SERVICE-VOITURE  

<img width="564" height="283" alt="image" src="https://github.com/user-attachments/assets/97c6202c-3e53-42f6-a306-ceec881ba19e" />


---

## 🟩 Gateway — Mode Statique  
### **Endpoints :**

#### ➤ `http://localhost:8888/clients`
<img width="574" height="282" alt="image" src="https://github.com/user-attachments/assets/41490dfe-087e-40cf-aae8-9c8c3cb3c697" />


#### ➤ `http://localhost:8888/client/1`
<img width="568" height="283" alt="image" src="https://github.com/user-attachments/assets/256d2e04-9fe0-445a-80cd-8c7031d4461d" />

#### ➤ `http://localhost:8888/voitures`
<img width="568" height="281" alt="image" src="https://github.com/user-attachments/assets/e3b99cae-9fb7-4c94-9286-98f0b4778e45" />

---

## 🟨 Gateway — Mode Dynamique (via Eureka)  
### **Endpoints :**

#### ➤ `http://localhost:8888/SERVICE-CLIENT/clients`
<img width="567" height="279" alt="image" src="https://github.com/user-attachments/assets/16b293b6-9bec-424a-8d37-eb8282cefe70" />

#### ➤ `http://localhost:8888/SERVICE-CLIENT/client/1`
<img width="571" height="281" alt="image" src="https://github.com/user-attachments/assets/5429a12d-963a-4b4c-a9ba-9c3a5b23c2fd" />

#### ➤ `http://localhost:8888/SERVICE-VOITURE/voitures`
<img width="571" height="279" alt="image" src="https://github.com/user-attachments/assets/d20eabdd-f3d1-458a-9bdf-d71ab41814fc" />

#### ➤ `http://localhost:8888/SERVICE-VOITURE/voitures/1`
<img width="569" height="281" alt="image" src="https://github.com/user-attachments/assets/8d1fadba-6ee3-45aa-a623-561269f00856" />

---

## 🟧 Microservice — SERVICE-CLIENT (Port 8088)  
### **Endpoints :**

#### ➤ `http://localhost:8088/clients`
<img width="571" height="280" alt="image" src="https://github.com/user-attachments/assets/a3913fe2-3228-4bc9-bc81-237c69985147" />

#### ➤ `http://localhost:8088/client/1`
<img width="569" height="278" alt="image" src="https://github.com/user-attachments/assets/67022784-128b-44f5-8bff-0553657a01c7" />

---

## 🟥 Microservice — SERVICE-VOITURE (Port 8089)  
### **Endpoints :**

#### ➤ `http://localhost:8089/voitures`
<img width="570" height="272" alt="image" src="https://github.com/user-attachments/assets/814110dd-3795-448a-bf5c-7e84b939b3eb" />

#### ➤ `http://localhost:8089/voitures/1`
<img width="570" height="271" alt="image" src="https://github.com/user-attachments/assets/5e82f716-b834-4da3-8554-cf6d4e731748" />

#### ➤ `http://localhost:8089/voitures/client/1`
<img width="573" height="279" alt="image" src="https://github.com/user-attachments/assets/bb21c478-ad0e-429c-a403-5985cf989561" />

---

