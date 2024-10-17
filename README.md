<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>React Quiz</title>
</head>
<body>
  <h1>React Quiz</h1>
  <form id="quiz-form">
    
    <!-- Question 1 -->
    <p>1. What hook is used to manage state in a functional React component?</p>
    <input type="radio" id="q1a" name="q1" value="a">
    <label for="q1a">useEffect</label><br>
    <input type="radio" id="q1b" name="q1" value="b">
    <label for="q1b">useState</label><br>
    <input type="radio" id="q1c" name="q1" value="c">
    <label for="q1c">useContext</label><br>
    <input type="radio" id="q1d" name="q1" value="d">
    <label for="q1d">useReducer</label><br>

    <!-- Question 2 -->
    <p>2. Which of the following is a side effect hook?</p>
    <input type="radio" id="q2a" name="q2" value="a">
    <label for="q2a">useState</label><br>
    <input type="radio" id="q2b" name="q2" value="b">
    <label for="q2b">useEffect</label><br>
    <input type="radio" id="q2c" name="q2" value="c">
    <label for="q2c">useRef</label><br>
    <input type="radio" id="q2d" name="q2" value="d">
    <label for="q2d">useMemo</label><br>

    <!-- Question 3 -->
    <p>3. Which method is used to create a new React project with Vite?</p>
    <input type="radio" id="q3a" name="q3" value="a">
    <label for="q3a">npx create-vite@latest my-app --template react</label><br>
    <input type="radio" id="q3b" name="q3" value="b">
    <label for="q3b">npm create-react-app my-app</label><br>
    <input type="radio" id="q3c" name="q3" value="c">
    <label for="q3c">npx create-react-app my-app</label><br>
    <input type="radio" id="q3d" name="q3" value="d">
    <label for="q3d">vite init react-app</label><br>

    <!-- Question 4 -->
    <p>4. What does the empty dependency array in useEffect([]) do?</p>
    <input type="radio" id="q4a" name="q4" value="a">
    <label for="q4a">It runs the effect only once on mount.</label><br>
    <input type="radio" id="q4b" name="q4" value="b">
    <label for="q4b">It runs the effect every time the component updates.</label><br>
    <input type="radio" id="q4c" name="q4" value="c">
    <label for="q4c">It prevents the effect from running.</label><br>
    <input type="radio" id="q4d" name="q4" value="d">
    <label for="q4d">It runs the effect after every re-render.</label><br>

    <!-- Question 5 -->
    <p>5. Which CSS framework is utility-first and often used with React?</p>
    <input type="radio" id="q5a" name="q5" value="a">
    <label for="q5a">Bootstrap</label><br>
    <input type="radio" id="q5b" name="q5" value="b">
    <label for="q5b">Materialize</label><br>
    <input type="radio" id="q5c" name="q5" value="c">
    <label for="q5c">Tailwind CSS</label><br>
    <input type="radio" id="q5d" name="q5" value="d">
    <label for="q5d">Bulma</label><br>

    <!-- Question 6 -->
    <p>6. How can you pass data from a parent component to a child component?</p>
    <input type="radio" id="q6a" name="q6" value="a">
    <label for="q6a">Through props</label><br>
    <input type="radio" id="q6b" name="q6" value="b">
    <label for="q6b">Through state</label><br>
    <input type="radio" id="q6c" name="q6" value="c">
    <label for="q6c">Through context</label><br>
    <input type="radio" id="q6d" name="q6" value="d">
    <label for="q6d">Through event handlers</label><br>

    <!-- Question 7 -->
    <p>7. Which of the following hooks is used to share global state in React?</p>
    <input type="radio" id="q7a" name="q7" value="a">
    <label for="q7a">useState</label><br>
    <input type="radio" id="q7b" name="q7" value="b">
    <label for="q7b">useEffect</label><br>
    <input type="radio" id="q7c" name="q7" value="c">
    <label for="q7c">useContext</label><br>
    <input type="radio" id="q7d" name="q7" value="d">
    <label for="q7d">useMemo</label><br>

    <!-- Continue with similar structure for Questions 8-30 -->

    <p>30. What is the benefit of using the `key` prop in React when rendering lists?</p>
    <input type="radio" id="q30a" name="q30" value="a">
    <label for="q30a">It helps React identify which items have changed.</label><br>
    <input type="radio" id="q30b" name="q30" value="b">
    <label for="q30b">It allows multiple components to share the same props.</label><br>
    <input type="radio" id="q30c" name="q30" value="c">
    <label for="q30c">It prevents state from resetting when the component re-renders.</label><br>
    <input type="radio" id="q30d" name="q30" value="d">
    <label for="q30d">It improves the performance of the useEffect hook.</label><br>

    <!-- Submit Button -->
    <input type="submit" value="Submit Quiz">
  </form>
</body>
</html>
