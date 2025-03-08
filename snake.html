<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>لعبة الثعبان</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden;
            background-color: black;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        canvas {
            background-color: black;
            border: 1px solid white;
            max-width: 100%;
            max-height: 100%;
        }
    </style>
</head>
<body>
    <canvas id="gameCanvas"></canvas>
    <script>
        const canvas = document.getElementById('gameCanvas');
        const ctx = canvas.getContext('2d');

        canvas.width = window.innerWidth * 0.8;
        canvas.height = window.innerHeight * 0.8;

        const gridSize = 20;
        let snake = [{ x: 10, y: 10 }];
        let direction = { x: 0, y: 0 };
        let food = { x: 5, y: 5 };
        let score = 0;

        function drawSnake() {
            ctx.fillStyle = 'white';
            snake.forEach(segment => {
                ctx.fillRect(segment.x * gridSize, segment.y * gridSize, gridSize, gridSize);
            });
        }

        function drawFood() {
            ctx.fillStyle = 'orange';
            ctx.fillRect(food.x * gridSize, food.y * gridSize, gridSize, gridSize);
        }

        function update() {
            const head = { x: snake[0].x + direction.x, y: snake[0].y + direction.y };

            if (head.x < 0 || head.x >= canvas.width / gridSize || head.y < 0 || head.y >= canvas.height / gridSize || snake.some(segment => segment.x === head.x && segment.y === head.y)) {
                alert('Game Over! Score: ' + score);
                snake = [{ x: 10, y: 10 }];
                direction = { x: 0, y: 0 };
                score = 0;
                return;
            }

            snake.unshift(head);

            if (head.x === food.x && head.y === food.y) {
                score++;
                food = {
                    x: Math.floor(Math.random() * (canvas.width / gridSize)),
                    y: Math.floor(Math.random() * (canvas.height / gridSize))
                };
            } else {
                snake.pop();
            }
        }

        function gameLoop() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            drawSnake();
            drawFood();
            update();
        }

        document.addEventListener('keydown', event => {
            switch (event.key) {
                case 'ArrowUp':
                    if (direction.y === 0) direction = { x: 0, y: -1 };
                    break;
                case 'ArrowDown':
                    if (direction.y === 0) direction = { x: 0, y: 1 };
                    break;
                case 'ArrowLeft':
                    if (direction.x === 0) direction = { x: -1, y: 0 };
                    break;
                case 'ArrowRight':
                    if (direction.x === 0) direction = { x: 1, y: 0 };
                    break;
            }
        });

        setInterval(gameLoop, 100);
    </script>
</body>
</html>
