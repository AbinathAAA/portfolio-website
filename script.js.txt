document.addEventListener('DOMContentLoaded', function() {
    const highlight = document.querySelector('.highlight');

    // Simple animation
    setInterval(() => {
        highlight.style.opacity = (highlight.style.opacity == 0 ? 1 : 0);
    }, 1000);
});
