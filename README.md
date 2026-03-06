# 👋 안녕하세요, 제 홈페이지에 오신 걸 환영합니다!

## 📸 My Photo Gallery
여기에 제가 찍은 사진들과 기록들을 남길 예정입니다.

### 갤러리 모음
<div align="center">
  <img src="images/photo1.jpg" height="300px" style="object-fit: cover; width: 200px; border-radius: 10px; margin: 5px;">
  <img src="images/photo2.jpg" height="300px" style="object-fit: cover; width: 200px; border-radius: 10px; margin: 5px;">
  <img src="images/photo3.jpg" height="300px" style="object-fit: cover; width: 200px; border-radius: 10px; margin: 5px;">
</div>

<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 15px; padding: 20px;">

  <div class="photo-card">
    <img src="images/photo1.jpg" alt="사진 1" class="gallery-img">
  </div>

  <div class="photo-card">
    <img src="images/photo2.jpg" alt="사진 2" class="gallery-img">
  </div>

  <div class="photo-card">
    <img src="images/photo3.jpg" alt="사진 3" class="gallery-img">
  </div>

</div>

<style>
  /* 사진을 담는 카드 (그림자 효과) */
  .photo-card {
    width: 200px; /* 카드의 가로 크기 고정 */
    height: 300px; /* 카드의 세로 크기 고정 */
    border-radius: 12px; /* 모서리 둥글게 */
    overflow: hidden; /* 영역 밖 사진 숨기기 (확대 시 필수) */
    box-shadow: 0 8px 16px rgba(0,0,0,0.15); /* 부드러운 그림자 효과 */
    transition: transform 0.3s ease, box-shadow 0.3s ease; /* 애니메이션 속도 */
    cursor: pointer; /* 마우스 커서 모양 변경 */
  }

  /* 마우스를 올렸을 때 카드 자체 효과 (살짝 떠오름) */
  .photo-card:hover {
    transform: translateY(-5px); /* 위로 살짝 이동 */
    box-shadow: 0 12px 24px rgba(0,0,0,0.25); /* 그림자 더 진하게 */
  }

  /* 실제 이미지 스타일 */
  .gallery-img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* 핵심: 비율 유지하며 영역 채우기 */
    transition: transform 0.5s ease; /* 확대 애니메이션 속도 */
  }

  /* 마우스를 올렸을 때 이미지 확대 (2배) */
  .photo-card:hover .gallery-img {
    transform: scale(2); /* 이미지만 2배 확대 */
  }
</style>


* **취미:** 사진 찍기, 코딩 공부
* **목표:** 멋진 나만의 웹사이트 완성하기
