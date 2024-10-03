// Select all <select> elements on the page
const selectElements = document.querySelectorAll('select');

// Iterate through each select element and disable it
selectElements.forEach(select => {
  select.disabled = true;
});
