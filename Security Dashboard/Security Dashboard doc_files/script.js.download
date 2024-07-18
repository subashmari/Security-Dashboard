document.addEventListener("DOMContentLoaded", function () {
    const navItems = document.querySelectorAll("nav li");
    const sections = document.querySelectorAll(".dashboard-section");

    navItems.forEach((item, index) => {
        item.addEventListener("click", () => {
            navItems.forEach((navItem) => navItem.classList.remove("active"));
            sections.forEach((section) => section.style.display = "none");

            item.classList.add("active");
            sections[index].style.display = "block";
        });
    });

    const passwordForm = document.getElementById("password-form");
    if (passwordForm) {
        passwordForm.addEventListener("submit", function (event) {
            event.preventDefault();
            // Password change logic here
        });
    }
});
