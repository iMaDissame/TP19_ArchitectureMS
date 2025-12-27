# Microservices — Tests & Endpoints

---

## 🟦 Eureka Server  
**Registered services visible:**
- GATEWAY  
- SERVICE-CLIENT  
- SERVICE-VOITURE  



---

## 🟩 Gateway — Mode Statique  
### **Endpoints :**

#### ➤ `http://localhost:8888/clients`


#### ➤ `http://localhost:8888/client/1`

#### ➤ `http://localhost:8888/voitures`

---

## 🟨 Gateway — Mode Dynamique (via Eureka)  
### **Endpoints :**

#### ➤ `http://localhost:8888/SERVICE-CLIENT/clients`

#### ➤ `http://localhost:8888/SERVICE-CLIENT/client/1`

#### ➤ `http://localhost:8888/SERVICE-VOITURE/voitures`

#### ➤ `http://localhost:8888/SERVICE-VOITURE/voitures/1`

---

## 🟧 Microservice — SERVICE-CLIENT (Port 8088)  
### **Endpoints :**

#### ➤ `http://localhost:8088/clients`

#### ➤ `http://localhost:8088/client/1`

---

## 🟥 Microservice — SERVICE-VOITURE (Port 8089)  
### **Endpoints :**

#### ➤ `http://localhost:8089/voitures`

#### ➤ `http://localhost:8089/voitures/1`

#### ➤ `http://localhost:8089/voitures/client/1`

---

