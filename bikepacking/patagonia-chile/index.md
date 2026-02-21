---
layout: page
title: "Patagonia Episode I: The Silent Horizon"
permalink: /bikepacking/patagonia-chile/
---


### **📷 Exploration Gallery**

<div align="center">
  <div id="gallery"></div>

  <script>
    const gallery = document.getElementById('gallery');
    for (let i = 1; i <= 49; i++) {
      const img = document.createElement('img');
      // 역순 출력: 49, 48, ..., 1
      img.src = `pata_${50-i}.jpg`; 
      img.style.width = '80%'; // 박사님, 50%보다는 80% 정도가 모바일/웹에서 보기에 더 시원할 겁니다!
      img.style.display = 'block'; // 세로로 깔끔하게 정렬
      img.style.marginBottom = '10px'; // 이미지 사이 간격
      gallery.appendChild(img);
    }
  </script>
</div>


---

### **📝 Journey Highlights**
* **Location:** Pucon, Chile to Punta Arenas, Chile
* **Expedition Style:** Solo Bikepacking

---

[← Back to Bikepacking Hub](/bikepacking/)
