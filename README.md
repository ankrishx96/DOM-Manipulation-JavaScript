## Adding Elements
document.append();  // Append Nodes & Strings || Append Multiple
document.appendChild(); // Append Nodes || Append Only 1 Node

## Creating Elements
document.createElement('div');

## Modifying Element Text
div.innerText = "Hello";
div.textContent = "Hello"

## Removing from HTML
const spanBye = document.querySelector("#bye");
spanBye.remove();
OR
div.removeChild(spanHi)

## Modify Elements Attributes

# Get Attributes
console.log(spanHi.getAttribute("id"));
console.log(spanHi.id);

# Set Attributes
 spanHi.setAttribute("id", "changed");
 spanBye.id = "newid";
 
 # Remove Attribute
     spanHi.removeAttribute("title");

// Data Set

      //  Get DataSet
      console.log(spanBye.dataset.name);

      //  Set Dataset
      spanBye.dataset.name = "Ankrish";
      spanBye.dataset.newdatapropery = "added"

// ClassList
      // Adding New Class
      spanHi.classList.add("new-class");

      # Removing Class
      spanHi.classList.remove("hi2");

      // Toggle
      spanHi.classList.toggle("hi");

// Styling
      spanHi.style.backgroundColor = "red";
      spanHi.style.border = "1px solid black";
