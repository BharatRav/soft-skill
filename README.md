# soft-skill

soft skills which employers look for while hiring

benefits of soft skill- to the organization and to the individual
</br>

soft skill refer to a cluster of personal qualities, habits, attitute, and
social graces that makes someone a good employee and compatible to work with.

# Hard skill vs Soft skill

hard skill is our technical knowledge to get job 
and soft skill to stay in the job.

# Good Soft skill

good soft skills will help you stand out in a crowd of mediocrity(equal type people in the crowd).

# personel Attributes which people look for
1 Honesty
</br>
2 Interpersonal skills
</br>
3 Integrity
</br>
4 Dedication
</br>
5 Manners & Etiquette
</br>
6 Ethics
</br>
7 Persistance
</br>
8 Pride in word
</br>
9 Good listener
</br>
and many more

# Anger Management
Anger Management is a psycho-therapeutic program for anger prevention and control.

# Anger
Anger is a strong feeling og aggrevation or irritation towards or about something.
<h2>Symptoms of anger</h2>
1 Clenched jaw or fists </br>
2 Increase in heart rate </br>
3 Red/flushed face </br>
4 shaking </br>
5 Feeling hot in the face or neck </br>
<h1>(Quote)Anger is one letter shorter of danger</h1>

# Controlling Anger
1 Think before you speak. </br>
2 Once you're calm, express your anger. </br>
3 Get some exercise. </br>
4 Don't hold a grudge.(sikayat) </br>

# Advanced Solutions & Therapies
1 Cognitive behavioural therapy </br>
2 Improvements in communication skills. </br>
3 Focus on problem -solving. </br>
4 Avoidance of problematic situations. </br>


<h1>(Quote)Holding onto ANGER is like drinking poison and expecting the other person to die. --BUDDHA--</h1>
//next will continue



const highlightButton = document.getElementById("highlight-button");
const clearButton = document.getElementById("clear-button");
const inputDate = document.getElementById("input-date");
const inputColor = document.getElementById("input-color");
const calendarDays = document.querySelectorAll(".calendar-day");

highlightButton.addEventListener("click", () => {
  const date = parseInt(inputDate.value);
  const color = inputColor.value;

  if (date > 0 && date <= 31) {
    calendarDays[date + 6].style.backgroundColor = color;
    inputDate.value = "";
    inputColor.value = "";
  }
});

clearButton.addEventListener("click", () => {
  calendarDays.forEach((day) => {
    day.style.backgroundColor = "";
  });
});
Jss




.calendar {
  display: grid;
  grid-template-columns: repeat(7, 100px);
  grid-template-rows: repeat(6, 100px);
  gap: 5px;
  margin-bottom: 10px;
}

.calendar-day {
  display: flex;
  justify-content: center;
  align-items: center;
  border: 1px solid rgb(0, 0, 0);
}

.input-wrapper {
  display: flex;
  align-items: center;
}

button {
  margin-left: 10px;
}
Css




<div class="calendar">
  <div class="calendar-day">Sun</div>
  <div class="calendar-day">Mon</div>
  <div class="calendar-day">Tue</div>
  <div class="calendar-day">Wed</div>
  <div class="calendar-day">Thu</div>
  <div class="calendar-day">Fri</div>
  <div class="calendar-day">Sat</div>
  
  <div class="calendar-day">1</div>
  <div class="calendar-day">2</div>
  <div class="calendar-day">3</div>
  <div class="calendar-day">4</div>
  <div class="calendar-day">5</div>
  <div class="calendar-day">6</div>
  <div class="calendar-day">7</div>
  <div class="calendar-day">8</div>
  <div class="calendar-day">9</div>
  <div class="calendar-day">10</div>
  <div class="calendar-day">11</div>
  <div class="calendar-day">12</div>
  <div class="calendar-day">13</div>
  <div class="calendar-day">14</div>
  <div class="calendar-day">15</div>
  <div class="calendar-day">16</div>
  <div class="calendar-day">17</div>
  <div class="calendar-day">18</div>
  <div class="calendar-day">19</div>
  <div class="calendar-day">20</div>
  <div class="calendar-day">21</div>
  <div class="calendar-day">22</div>
  <div class="calendar-day">23</div>
  <div class="calendar-day">24</div>
  <div class="calendar-day">25</div>
  <div class="calendar-day">26</div>
  <div class="calendar-day">27</div>
  <div class="calendar-day">28</div>
  <div class="calendar-day">29</div>
  <div class="calendar-day">30</div>
  <div class="calendar-day">31</div>
</div>

<div class="input-wrapper">
  <label for="input-date">Date:</label>
  <input type="number" id="input-date">
  
  <label for="input-color">Color:</label>
  <input type="text" id="input-color">
  
  <button id="highlight-button">Highlight Date</button>
  <button id="clear-button">Clear All</button>
</div>
Html
