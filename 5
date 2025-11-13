<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Feedback System</title>
  <style>
    body {
      font-family: "Poppins", sans-serif;
      background: linear-gradient(135deg, #6a11cb, #2575fc);
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;
      padding: 20px;
    }

    h1 {
      color: #fff;
      margin-bottom: 20px;
    }

    .container {
      background: #fff;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
      width: 320px;
      text-align: center;
    }

    .stars {
      display: flex;
      justify-content: center;
      gap: 10px;
      margin: 15px 0;
    }

    .star {
      font-size: 25px;
      cursor: pointer;
      color: #ccc;
      transition: 0.3s;
    }

    .star.active,
    .star:hover {
      color: gold;
      transform: scale(1.2);
    }

    textarea {
      width: 100%;
      height: 80px;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 10px;
      resize: none;
      font-size: 14px;
    }

    button {
      background: #6a11cb;
      color: #fff;
      border: none;
      padding: 10px;
      width: 100%;
      border-radius: 10px;
      cursor: pointer;
      font-size: 16px;
      margin-top: 10px;
      transition: 0.3s;
    }

    button:hover {
      background: #2575fc;
    }

    .output {
      margin-top: 20px;
      width: 100%;
      background: #f9f9f9;
      border-radius: 10px;
      padding: 10px;
      max-height: 200px;
      overflow-y: auto;
      text-align: left;
    }

    .feedback-item {
      background: #fff;
      padding: 10px;
      border-radius: 8px;
      margin-bottom: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .rating {
      color: gold;
      font-size: 18px;
    }
  </style>
</head>
<body>

  <h1>⭐ Feedback System</h1>

  <div class="container">
    <div class="stars" id="stars">
      <span class="star" data-value="1">★</span>
      <span class="star" data-value="2">★</span>
      <span class="star" data-value="3">★</span>
      <span class="star" data-value="4">★</span>
      <span class="star" data-value="5">★</span>
    </div>

    <textarea id="comment" placeholder="Write your feedback..."></textarea>
    <button onclick="submitFeedback()">Submit</button>

    <div class="output" id="feedbackList"></div>
  </div>

  <script>
    let selectedRating = 0;
    const stars = document.querySelectorAll('.star');
    const feedbackList = document.getElementById('feedbackList');

    stars.forEach(star => {
      star.addEventListener('click', () => {
        selectedRating = star.getAttribute('data-value');
        stars.forEach(s => s.classList.remove('active'));
        for (let i = 0; i < selectedRating; i++) {
          stars[i].classList.add('active');
        }
      });
    });

    function submitFeedback() {
      const comment = document.getElementById('comment').value.trim();
      if (!selectedRating || !comment) {
        alert("Please select a rating and enter feedback!");
        return;
      }

      const feedbackItem = document.createElement('div');
      feedbackItem.classList.add('feedback-item');
      feedbackItem.innerHTML = `
        <div class="rating">${'★'.repeat(selectedRating)}</div>
        <p>${comment}</p>
      `;

      feedbackList.prepend(feedbackItem);
      document.getElementById('comment').value = '';
      stars.forEach(s => s.classList.remove('active'));
      selectedRating = 0;
    }
  </script>

</body>
</html>
