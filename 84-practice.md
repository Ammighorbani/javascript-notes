# Practice

```
var scores = 0

var questions = [

    {id: 1, question: "what is windows", answer: "operating system"},
    {id: 2, question: "why we use key-board", answer: "to writing"},
    {id: 3, question: "why we use monitor", answer: "to watch screen"},
    
]

var showQuestionandanswers = questions.forEach(function(question) {

    console.log(question)

})

var showquestion = null
var answer = ""


for (var i = 0; i < questions.length; i++) {

    showquestion = questions[i]
    answer = prompt(showquestion.question + "\n" + "enter your answer")


    if (answer === showquestion.answer) {

        scores += 1

    } else {

        scores -= 1

    }

}

console.log(scores)
```