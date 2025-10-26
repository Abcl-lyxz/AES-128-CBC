# AES-128 CBC Implementation in C

This project is a **clean, self-contained AES-128 (CBC mode)** implementation written in pure C.  
It provides both encryption and decryption routines with **PKCS#7 padding**, **constant-time S-box**,  
and secure **IV randomization** using `/dev/urandom`.

---

## 🔒 Features

- ✅ AES-128 encryption and decryption (10 rounds)
- ✅ CBC (Cipher Block Chaining) mode
- ✅ PKCS#7 padding / unpadding
- ✅ Constant-time S-box lookups (resistant to timing attacks)
- ✅ Random IV generation from `/dev/urandom`
- ✅ Works entirely in-memory (no external dependencies)
- ✅ Clean, readable, and modular C code

---

## 📂 File Structure

