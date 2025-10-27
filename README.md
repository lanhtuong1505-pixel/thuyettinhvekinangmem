#SOPC GROUP 
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Thuyết trình: Vai trò của Kỹ năng Mềm đối với Tuổi trẻ</title>
<style>
  body {
    font-family: "Segoe UI", sans-serif;
    margin: 0;
    overflow: hidden;
    background: linear-gradient(to bottom, #faf9f6, #e8edf3);
    position: relative;
  }

  /* Slide cơ bản */
  .slide {
    display: none;
    opacity: 0;
    height: 100vh;
    padding: 60px;
    text-align: center;
    transition: opacity 1s ease-in-out;
  }
  .active {
    display: block;
    opacity: 1;
  }

  h1, h2 {
    color: #2a4d69;
  }
  p {
    font-size: 20px;
    color: #333;
    max-width: 900px;
    margin: 15px auto;
    line-height: 1.7;
  }
  img {
    width: 400px;
    border-radius: 12px;
    margin: 20px auto;
    box-shadow: 0 4px 12px rgba(0,0,0,0.25);
  }

  /* Nút chuyển trang */
  button {
    position: fixed;
    bottom: 20px;
    padding: 12px 25px;
    border: none;
    background: #4b86b4;
    color: white;
    font-size: 18px;
    border-radius: 8px;
    cursor: pointer;
    box-shadow: 0 3px 8px rgba(0,0,0,0.2);
    transition: background 0.3s ease;
  }
  button:hover {
    background: #345d80;
  }
  #nextBtn { right: 40px; }
  #prevBtn { left: 40px; }

  /* Lá vàng rơi */
  .leaf {
    position: absolute;
    top: -50px;
    width: 35px;
    height: 35px;
    background: url('https://png.pngtree.com/png-vector/20231023/ourmid/pngtree-yellow-leaf-png-image_10105868.png') no-repeat center/contain;
    opacity: 0.8;
    animation: fall linear infinite;
  }

  @keyframes fall {
    0% {
      transform: translateY(0) rotate(0deg);
      opacity: 0.9;
    }
    100% {
      transform: translateY(110vh) rotate(360deg);
      opacity: 0;
    }
  }
</style>
</head>
<body>

<!-- Slide 1 -->
<div class="slide active" id="slide1">
  <h1>Vai trò của Kỹ năng Mềm đối với Tuổi trẻ</h1>
  <p>Kính chào quý thầy cô và các bạn. Em là [Tên của bạn]. Hôm nay, em xin được trình bày về một chủ đề gần gũi nhưng rất quan trọng trong hành trình trưởng thành của mỗi người trẻ: <b>Vai trò của kỹ năng mềm đối với tuổi trẻ</b>.</p>
  <img src="https://img.freepik.com/free-vector/people-giving-high-five-concept-illustration_114360-1064.jpg" alt="Chào hỏi">
</div>

<!-- Slide 2 -->
<div class="slide" id="slide2">
  <h2>I. Kỹ năng Mềm là gì?</h2>
  <p>Kỹ năng mềm là tập hợp những phẩm chất, thói quen và khả năng liên quan đến cảm xúc, giao tiếp, tư duy và cách ứng xử của con người. Đây không phải là kiến thức chuyên môn, mà là cách chúng ta làm việc, tương tác và quản lý bản thân trong cuộc sống. Ví dụ như kỹ năng giao tiếp, làm việc nhóm, tư duy phản biện, quản lý thời gian hay khả năng thích ứng.</p>
  <img src="https://img.freepik.com/free-vector/soft-skills-concept-illustration_114360-8186.jpg" alt="Soft skills">
</div>

<!-- Slide 3 -->
<div class="slide" id="slide3">
  <h2>II. Vai trò của Kỹ năng Mềm</h2>
  <p>Kỹ năng mềm chính là “chiếc chìa khóa thứ hai” mở ra cánh cửa thành công. Một người có thể giỏi chuyên môn, nhưng nếu thiếu khả năng giao tiếp, hợp tác hoặc giải quyết vấn đề, họ rất dễ bị tụt lại phía sau. Nhiều nghiên cứu cho thấy hơn 75% sự thành công trong công việc đến từ kỹ năng mềm, chứ không chỉ từ kiến thức chuyên môn.</p>
  <img src="https://img.freepik.com/free-vector/leadership-concept-illustration_114360-1081.jpg" alt="Leadership">
</div>

<!-- Slide 4 -->
<div class="slide" id="slide4">
  <h2>III. Tác động đến đời sống của giới trẻ</h2>
  <p>Với tuổi trẻ, kỹ năng mềm không chỉ giúp học tốt hơn mà còn giúp chúng ta tự tin hơn trong giao tiếp, kiểm soát cảm xúc và xây dựng mối quan hệ tích cực. Nhờ kỹ năng lắng nghe, thấu hiểu và làm việc nhóm, chúng ta dễ hòa nhập, được bạn bè và đồng nghiệp tin tưởng. Kỹ năng mềm cũng giúp vượt qua thất bại, thích nghi trong môi trường mới và định hướng bản thân tốt hơn.</p>
  <img src="https://img.freepik.com/free-vector/goal-achievement-concept-illustration_114360-1422.jpg" alt="Success">
</div>

<!-- Slide 5 -->
<div class="slide" id="slide5">
  <h2>IV. Hậu quả khi thiếu kỹ năng mềm</h2>
  <p>Ngược lại, thiếu kỹ năng mềm khiến nhiều bạn trẻ dễ bị cô lập, thiếu tự tin và khó hòa nhập trong môi trường học tập hoặc làm việc. Không ít sinh viên học giỏi nhưng lại gặp khó khăn trong việc thuyết trình, phỏng vấn hay làm việc nhóm. Điều đó khiến họ đánh mất nhiều cơ hội quý giá cho sự nghiệp tương lai.</p>
  <img src="https://img.freepik.com/free-vector/conflict-concept-illustration_114360-2723.jpg" alt="Conflict">
</div>

<!-- Slide 6 -->
<div class="slide" id="slide6">
  <h2>V. Cách rèn luyện kỹ năng mềm</h2>
  <p>Để phát triển kỹ năng mềm, chúng ta cần bắt đầu từ những hành động nhỏ: tham gia các hoạt động tập thể, câu lạc bộ, thử sức với vai trò lãnh đạo, luyện thuyết trình, hoặc học cách lắng nghe và làm việc nhóm. Hãy dám nói, dám làm và dám thể hiện bản thân. Chính quá trình này giúp chúng ta trưởng thành, tự tin và bản lĩnh hơn mỗi ngày.</p>
  <img src="https://img.freepik.com/free-vector/teamwork-concept-illustration_114360-9026.jpg" alt="Teamwork">
</div>

<!-- Slide 7 -->
<div class="slide" id="slide7">
  <h2>VI. Kết luận</h2>
  <p>Tóm lại, kỹ năng mềm không chỉ là yếu tố phụ mà là nền tảng giúp tuổi trẻ tiến xa hơn trong học tập và cuộc sống. Nó giúp chúng ta không chỉ “biết” mà còn “làm được”, không chỉ “thành công” mà còn “thành nhân”. Vì vậy, ngay từ hôm nay, hãy bắt đầu rèn luyện kỹ năng mềm – hành trang quý giá nhất trên con đường hướng đến tương lai.</p>
  <p><b>Em xin chân thành cảm ơn quý thầy cô và các bạn đã lắng nghe!</b></p>
</div>

<!-- Nút chuyển -->
<button id="prevBtn">← Trước</button>
<button id="nextBtn">Tiếp →</button>

<script>
  // Slide chuyển động
  let current = 1;
  const slides = document.querySelectorAll(".slide");

  function showSlide(n) {
    slides.forEach(s => s.classList.remove("active"));
    slides[n-1].classList.add("active");
  }

  document.getElementById("nextBtn").onclick = () => {
    current++;
    if (current > slides.length) current = slides.length;
    showSlide(current);
  }

  document.getElementById("prevBtn").onclick = () => {
    current--;
    if (current < 1) current = 1;
    showSlide(current);
  }

  // Lá vàng rơi (nhiều hơn)
  const numLeaves = 30;
  for (let i = 0; i < numLeaves; i++) {
    const leaf = document.createElement("div");
    leaf.classList.add("leaf");
    leaf.style.left = Math.random() * 100 + "vw";
    leaf.style.animationDuration = 5 + Math.random() * 7 + "s";
    leaf.style.animationDelay = Math.random() * 5 + "s";
    leaf.style.transform = `rotate(${Math.random() * 360}deg)`;
    document.body.appendChild(leaf);
  }
</script>

</body>
</html>
