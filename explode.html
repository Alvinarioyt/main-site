var confetti = (function() {
    // Private variables and functions
    var canvas, ctx;
    var confettiParticles = [];
    var confettiColors = ['#f44336', '#2196f3', '#4caf50', '#ffeb3b', '#ff9800'];

    // Function to create a confetti particle
    function createConfettiParticle() {
        return {
            x: Math.random() * canvas.width, // Random x position
            y: -10, // Start from the top of the canvas
            angle: Math.random() * Math.PI * 2, // Random angle
            radius: Math.random() * 5 + 5, // Random radius
            color: confettiColors[Math.floor(Math.random() * confettiColors.length)] // Random color
        };
    }

    // Function to draw a confetti particle
    function drawConfettiParticle(particle) {
        ctx.beginPath();
        ctx.arc(particle.x, particle.y, particle.radius, 0, Math.PI * 2);
        ctx.fillStyle = particle.color;
        ctx.fill();
    }

    // Function to update confetti particle positions
    function updateConfettiParticles() {
        for (var i = 0; i < confettiParticles.length; i++) {
            var p = confettiParticles[i];
            p.y += Math.sin(p.angle) * 5; // Move vertically with sine function
            p.x += Math.cos(p.angle) * 2; // Move horizontally with cosine function
            if (p.y > canvas.height) {
                p.y = -10; // Reset particle position when it goes below the canvas
            }
        }
    }

    // Function to render confetti animation
    function renderConfetti() {
        ctx.clearRect(0, 0, canvas.width, canvas.height); // Clear canvas
        for (var i = 0; i < confettiParticles.length; i++) {
            var p = confettiParticles[i];
            drawConfettiParticle(p); // Draw each confetti particle
        }
        updateConfettiParticles(); // Update confetti particle positions
        requestAnimationFrame(renderConfetti); // Repeat animation
    }

    // Public method to start the confetti animation
    function start(canvasId) {
        canvas = document.getElementById(canvasId);
        if (canvas) {
            ctx = canvas.getContext('2d');
            // Create confetti particles
            for (var i = 0; i < 100; i++) {
                confettiParticles.push(createConfettiParticle());
            }
            renderConfetti(); // Start rendering confetti animation
        } else {
            console.error("Canvas element with id '" + canvasId + "' not found.");
        }
    }

    // Public interface
    return {
        start: start
    };
})();
