<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>A Quiz Pour Mon Bébé d'Amour</title>
<style>
  body { font-family: Arial, sans-serif; background: #ffe6f0; color: #333; padding: 20px; }
  h1 { color: #d6336c; text-align: center; font-size: 2.5em;}
  .question { margin: 20px 0; }
  .options { list-style: none; padding: 0; }
  .options li, .options label { background: white; margin: 8px 0; padding: 14px; border-radius: 8px; cursor: pointer; border: 2px solid #d6336c; font-size: 1.1em; transition: 0.2s; display: block;}
  .options li:hover, .options label:hover { background: #d6336c; color: white; }
  .options input[type="checkbox"] { margin-right: 10px; transform: scale(1.3);}
  .selected { background: #d6336c !important; color: white !important; }
  .submit-btn, .restart-btn { background: #d6336c; color: white; padding: 14px 28px; border: none; border-radius: 8px; cursor: pointer; font-size: 18px; margin-top: 24px; display: block; margin-left: auto; margin-right: auto;}
  .result { margin-top: 28px; font-weight: bold; color: #d6336c; text-align: center; font-size: 1.5em;}
  .hide { display: none; }
  @media (max-width: 600px) {
    h1 { font-size: 1.5em;}
    .submit-btn, .restart-btn { font-size: 1em;}
  }
</style>
</head>
<body>
<h1>A Quiz Pour Mon Bébé d'Amour 💖</h1>
<form id="quizForm">

<div class="question" id="q1">
  <p>Welcome hbibiii lfeeen😍♥️</p>
  <p>La date Li te9rihan bdina feha la relation dyalna</p>
  <ul class="options">
    <li data-answer="28/09">28/09</li>
    <li data-answer="02/10">02/10</li>
    <li data-answer="04/10">04/10</li>
    <li data-answer="06/10">06/10</li>
  </ul>
  <p class="feedback"></p>
</div>

<div class="question" id="q2">
  <p>Awal 3tiraf direct kan binatna wach kan</p>
  <ul class="options">
    <li data-answer="Écrit">Écrit</li>
    <li data-answer="Oral">Oral</li>
  </ul>
  <p class="feedback"></p>
</div>

<div class="question" id="q3">
  <p>Fen kanet leblasa</p>
  <ul class="options">
    <li data-answer="Train">Train</li>
    <li data-answer="Bvt">Bvt</li>
    <li data-answer="KNA Bara">KNA Bara</li>
  </ul>
  <p class="feedback"></p>
</div>

<div class="question" id="q4">
  <p>My love language for u was</p>
  <ul class="options">
    <li data-answer="Physical touch">Physical touch</li>
    <li data-answer="Cooking">Cooking</li>
    <li data-answer="Drawing">Drawing</li>
  </ul>
  <p class="feedback"></p>
</div>

<div class="question" id="q5">
  <p>Aktar haja khalatni n3rf Ra knbghik</p>
  <ul class="options">
    <li data-answer="Knfaker fik">Knfaker fik</li>
    <li data-answer="Knbghi nb9a m3k">Knbghi nb9a m3k</li>
    <li data-answer="Fch kn9isek">Fch kn9isek</li>
    <li data-answer="Fach knchuf 3inik">Fach knchuf 3inik</li>
  </ul>
  <p class="feedback"></p>
</div>

<div class="question" id="q6">
  <p>How I feel safe more around u (اختار جوج)</p>
  <ul class="options">
    <label><input type="checkbox" value="Hold my hands" />Hold my hands</label>
    <label><input type="checkbox" value="Touch my hair" />Touch my hair</label>
    <label><input type="checkbox" value="Touch my back" />Touch my back</label>
  </ul>
  <p class="feedback"></p>
</div>

<div class="question" id="q7">
  <p>N3as 7dak wydi fydek</p>
  <ul class="options">
    <li data-answer="Tedwi m3aya wtsuportini wtfhamni">Tedwi m3aya wtsuportini wtfhamni</li>
    <li data-answer="T9is Li rasi wt9oli I'm with I">T9is Li rasi wt9oli I'm with I</li>
  </ul>
  <p class="feedback"></p>
</div>

<div class="question" id="q8">
  <p>Katkharbe9ni ktar when u</p>
  <ul class="options">
    <li data-answer="Kat9areb MNi bzaf w3ini ktjy f3inek">Kat9areb MNi bzaf w3ini ktjy f3inek</li>
    <li data-answer="Kat9is dahri">Kat9is dahri</li>
    <li data-answer="Katgoli chi haja eheem ms zwenaa bzaf">Katgoli chi haja eheem ms zwenaa bzaf</li>
  </ul>
  <p class="feedback"></p>
</div>

<div class="question" id="q9">
  <p>Kanbghi n9is ktaaar</p>
  <ul class="options">
    <li data-answer="ur hands">ur hands</li>
    <li data-answer="ur lips">ur lips</li>
    <li data-answer="sdiyer">sdiyer</li>
  </ul>
  <p class="feedback"></p>
</div>

<div class="question" id="q10">
  <p>Chno aktar haja kat3sbni</p>
  <ul class="options">
    <li data-answer="Fch katsecroli Wana hdak">Fch katsecroli Wana hdak</li>
    <li data-answer="Makatbghich t9ra">Makatbghich t9ra</li>
    <li data-answer="Katb9a dhak m3a drary and not me">Katb9a dhak m3a drary and not me</li>
  </ul>
  <p class="feedback"></p>
</div>

<button type="button" class="submit-btn">Show My Result!</button>
<div class="result hide"></div>
<button type="button" class="restart-btn hide">Restart Quiz</button>

<div class="question">
  <p>رسالة ختام</p>
  <p style="color:#d6336c; font-weight:bold; font-size:1.2em; text-align:center;">
    Amaaniiii love u so much 🥺💗. Ur eyes ur personality Your manhood ur responsibility when ur my adult man when ur little baby habibyy🍼🐥 when ur happy ur mad just I'm obsessed and obsessed and obsessed ghzali kbidty♥️🥺 allah ykhalik liliiiii yarpyyyyy
  </p>
</div>
</form>

<script>
  // Correct answers for scoring and feedback
  const answers = {
    q1: "02/10",
    q2: "Oral",
    q3: "Train",
    q4: "Physical touch",
    q5: "Knfaker fik",
    q6: ["Hold my hands", "Touch my hair"], // allow two choices
    q7: "Tedwi m3aya wtsuportini wtfhamni",
    q8: "Kat9areb MNi bzaf w3ini ktjy f3inek",
    q9: "ur hands",
    q10: "Fch katsecroli Wana hdak"
  };
  const feedbacks = {
    q1: {
      "02/10": "Olalalala Amani hbibi kanbghiiiik🥺💗",
      "default": "Ummm nonono Amani🥺😭"
    },
    q2: {
      "Oral": "Yes! I still remember your cute voice 😍",
      "default": "Noo, but your words are always sweet! 💌"
    },
    q3: {
      "Train": "Correct! That moment was unforgettable 🚂💕",
      "default": "Nope, that's not it but I love our every moment 😘"
    },
    q4: {
      "Physical touch": "Of course! Hugs and cuddles forever 💞",
      "default": "I love doing all that for you, but there's one that's most special! 😚"
    },
    q5: {
      "Knfaker fik": "True! You live in my mind rent-free 🧠💖",
      "default": "That's cute but there's something deeper 🥺"
    },
    q6: "Those are the sweetest! Always makes me feel safe 💗",
    q7: {
      "Tedwi m3aya wtsuportini wtfhamni": "Exactly! Your support means everything to me 🙏",
      "default": "That's sweet, but support is my real comfort! 🥰"
    },
    q8: {
      "Kat9areb MNi bzaf w3ini ktjy f3inek": "You know me so well, I melt every time! 😍",
      "default": "That's cute, but the real weakness is your eyes on me! 👀💗"
    },
    q9: {
      "ur hands": "Yesss! I love holding your hands 👐💕",
      "default": "That's sweet, but hands are my favorite! 😘"
    },
    q10: {
      "Fch katsecroli Wana hdak": "Yes! I want all your attention 😤💖",
      "default": "That's not it, but I love you anyway! 😅"
    }
  };

  // Option click handler for radio-style questions
  document.querySelectorAll('.question').forEach(q => {
    const feedback = q.querySelector('.feedback');
    if (q.id === "q6") {
      // For checkboxes, handle separately on submit
      return;
    }
    const options = q.querySelectorAll('.options li');
    options.forEach(option => {
      option.addEventListener('click', () => {
        options.forEach(o => o.classList.remove('selected'));
        option.classList.add('selected');
        // Immediate feedback
        if (feedback) {
          const ans = option.dataset.answer;
          feedback.textContent = feedbacks[q.id][ans] || feedbacks[q.id]["default"];
        }
      });
    });
  });

  // Submit button handler
  document.querySelector('.submit-btn').onclick = function() {
    let score = 0;
    let total = 10;
    let resultMsg = "";
    let q6chosen = [];
    // Loop through questions and check answers
    for (let i = 1; i <= total; i++) {
      const qid = 'q' + i;
      const q = document.getElementById(qid);
      const feedback = q.querySelector('.feedback');
      let userAns = "";
      if (qid === "q6") {
        // Checkboxes
        q6chosen = Array.from(q.querySelectorAll('input[type="checkbox"]:checked')).map(cb => cb.value);
        if (q6chosen.length === 2 &&
            q6chosen.includes(answers.q6[0]) &&
            q6chosen.includes(answers.q6[1])) {
          score++;
          feedback.textContent = feedbacks.q6;
        } else {
          feedback.textContent = "Just two make me feel safest! Try again 😬";
        }
      } else {
        // Radio
        const selected = q.querySelector('.options li.selected');
        if (selected) userAns = selected.dataset.answer;
        // Score
        if (userAns === answers[qid]) score++;
        // Feedback already set on click
        if (feedback && !feedback.textContent)
          feedback.textContent = feedbacks[qid][userAns] || feedbacks[qid]["default"];
      }
    }
    // Result
    const resultDiv = document.querySelector('.result');
    resultDiv.classList.remove('hide');
    let emoji = score === total ? "💖💯" : score > 7 ? "😍🥰" : score > 4 ? "😊" : "🥺";
    resultMsg = `${emoji} You scored <span style="color:#d6336c">${score}</span> out of ${total}!<br> 
      ${score === total ? "Perfect! You're truly my soulmate 😍" :
        score > 7 ? "Almost perfect! You know me so well! 💗" :
        score > 4 ? "Not bad! But there's room for more love! 😘" :
        "Oh, you need to listen to my heart more! 😅"}<br>
      <span style="font-size:1.2em;">Amaaniiii love u so much 🥺💗 ghzali kbidty♥️</span>`;
    resultDiv.innerHTML = resultMsg;
    document.querySelector('.restart-btn').classList.remove('hide');
    this.classList.add('hide');
  };

  // Restart button handler
  document.querySelector('.restart-btn').onclick = function() {
    location.reload();
  };
</script>
</body>
</html>
