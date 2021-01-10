# hQuery
A brand new JavaScript Libary that allows you to code with h
Some example code:
```js
h("h1").toggleClass("bigtext", "herotext").hasClass("herotext");
h("#myDiv").append(
    "<em>h!</em>"
);
h("#super").attr(["placeholder", "disabled"], ["your name", "true"]);
h("#super").attr("placeholder");
h("#myDiv").children();

h("body").data("kasztan", "oczywiscie ze nie");

h("#myDiv").find("i").attr("style", "color: red");

h("b").on("click", function() {
    alert("h!");
});

h("b").parent();
```
