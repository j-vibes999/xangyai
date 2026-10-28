# ຊ້າງໃຫຍ່ ໂຢເກີດ (Chang Yai Yogurt)

> ຄວາມສຸກ ທຸກຊ່ວງເວລາ — ເວັບໄຊໂຢເກີດເນື້ອແໜ້ນ ຜະລິດທີ່ນະຄອນຫຼວງວຽງຈັນ

ເວັບໄຊທາງການຂອງ **ຊ້າງໃຫຍ່ ໂຢເກີດ** (Chang Yai Dairy) ແບບ Interactive Creative Web ພ້ອມປະສົບການຕັກໂຢເກີດ ແລະ ຄົ້ນຫາຕູ້ເຢັນສີທອງໃນນະຄອນຫຼວງວຽງຈັນ.

---

## ✨ ຈຸດເດັ່ນຂອງເວັບໄຊ (Features)

- **Interactive Yogurt Cup**: ດຶງຝາຖ້ວຍໂຢເກີດພ້ອມລະບົບຟີຊິກສ໌ Spring & Drag
- **WebGL Yogurt Jiggle Shader**: ແຕະໜ້າໂຢເກີດເພື່ອສຳຜັດຄວາມດຶ໋ງດັ໋ງຂອງເນື້ອໂຢເກີດ
- **Scroll-driven Scoop Animation**: ເລື່ອນລົງເພື່ອເບິ່ງອະນິເມຊັນຕັກໂຢເກີດແບບ Frame-by-frame
- **Built-in Web Audio API**: ສຽງປະກອບສັງເຄາະໃນຕົວ (Pop, Boing, Chimes, Whoosh) ໂດຍບໍ່ຕ້ອງໂຫຼດໄຟລ໌ສຽງເພີ່ມເຕີມ
- **ຊອກຫາຕູ້ສີທອງ (Find the Gold Fridge)**: ແຜນທີ່ Google Maps ແລະ ລາຍຊື່ 10 ຈຸດຕັ້ງຕູ້ແຊ່ສີທອງໃນນະຄອນຫຼວງວຽງຈັນ ພ້ອມລິ້ງນຳທາງ
- **Ultra Lightweight**: ເວັບໄຊ Static ລ້ວນໆ (HTML5, Modern CSS, Vanilla JS) ໂຫຼດໄວ ແລະ ຮອງຮັບມືຖືທຸກຂະໜາດ

---

## 🚀 ວິທີຂຶ້ນເວັບ (Deployment)

1. ເວັບນີ້ເປັນໄຟລ໌ static ທັງໝົດ ບໍ່ມີຖານຂໍ້ມູນ ບໍ່ຕ້ອງຕັ້ງຄ່າເຊີບເວີ
2. ອັບໂຫຼດທຸກໄຟລ໌ຂຶ້ນ root directory ຂອງເວັບ (ໃຫ້ `index.html` ຢູ່ຊັ້ນເທິງສຸດ)
   - ຮອງຮັບ Cloudflare Pages, Vercel, Netlify, cPanel, Nginx, Apache
3. ເປີດຜ່ານ **HTTPS** (ການເປີດໂດຍ double-click ຈາກເຄື່ອງຈະບໍ່ເຮັດວຽກຍ້ອນ WebGL/Fetch API)
4. **ໝາຍເຫດສຳລັບ ສປປ ລາວ**: ໂດເມນຟຣີ `*.pages.dev` ແລະ `*.vercel.app` ມັກຈະເປີດບໍ່ໄດ້ໃນລາວ ແນະນຳໃຫ້ຜູກກັບ Custom Domain ຂອງຕົນເອງ

---

## 📁 ໂຄງສ້າງໄຟລ໌ (Project Structure)

```text
├── assets/             # CSS & JS Bundle
├── data/
│   └── fridges.json    # ພິກັດຕູ້ແຊ່ສີທອງ 10 ແຫ່ງ
├── frames/
│   └── scoop3/         # ເຟຣມອະນິເມຊັນຕັກໂຢເກີດ (001.webp - 117.webp)
├── img/                # ຮູບພາບສິນຄ້າ ແລະ ມາສະຄອດ
├── favicon.svg
├── index.html
└── README.md
```

---

© 2026 Chang Yai Dairy. All rights reserved.
