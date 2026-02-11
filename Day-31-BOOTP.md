# Day 31 – BOOTP (Bootstrap Protocol)

## 🔹 What is BOOTP?

BOOTP (Bootstrap Protocol) is a network protocol used to automatically assign an IP address to devices during boot time.

It is the predecessor of DHCP.

---

## 🔹 Why BOOTP Was Created

- Used for diskless workstations
- Automatically assigns IP address at startup
- Provides boot file name & server information

---

## 🔹 How BOOTP Works

1. Client sends broadcast request
2. BOOTP server receives request
3. Server responds with:
   - IP address
   - Subnet mask
   - Default gateway
   - Boot file name

---

## 🔹 Ports Used

- UDP Port 67 → Server
- UDP Port 68 → Client

---

## 🔹 BOOTP vs DHCP

| Feature | BOOTP | DHCP |
|----------|--------|-------|
| Address Assignment | Static | Dynamic |
| Flexibility | Limited | High |
| Configuration | Manual | Automatic |
| Modern Usage | Rare | Common |

---

## 🔹 Limitations

- Manual configuration required
- No automatic lease renewal
- Less scalable

---

## 🔹 Security Relevance

- Useful in legacy traffic analysis
- Important in packet capture investigation
- Foundation for understanding DHCP attacks

---

## 🔹 Key Takeaway

BOOTP laid the foundation for DHCP and automatic network configuration.
Understanding it strengthens networking fundamentals for SOC & Blue Team roles.
