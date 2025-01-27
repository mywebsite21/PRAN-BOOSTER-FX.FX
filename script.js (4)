// Function to switch between sections
function showSection(sectionId) {
  // Hide all sections
  const sections = document.querySelectorAll('.section');
  sections.forEach(section => {
    section.classList.add('hidden');
    section.classList.remove('visible');
  });

  // Show the clicked section
  const activeSection = document.getElementById(sectionId);
  activeSection.classList.remove('hidden');
  activeSection.classList.add('visible');
}

// JavaScript to hide/show the header on scroll
let prevScrollPos = window.pageYOffset;

window.onscroll = function() {
  let currentScrollPos = window.pageYOffset;
  const header = document.getElementById("header");

  if (prevScrollPos > currentScrollPos) {
    header.classList.remove("sticky"); // Show header when scrolling up
  } else {
    header.classList.add("sticky"); // Hide header when scrolling down
  }
  prevScrollPos = currentScrollPos;
};