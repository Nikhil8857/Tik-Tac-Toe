body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f5f5f5;
    margin: 0;
}

.game-container {
    text-align: center;
}

.board {
    display: grid;
    grid-template-columns: repeat(3, 100px);
    grid-template-rows: repeat(3, 100px);
    gap: 5px;
    margin: 20px auto;
}

.cell {
    width: 100px;
    height: 100px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 2em;
    background-color: #fff;
    border: 1px solid #ccc;
    cursor: pointer;
}

.cell:hover {
    background-color: #f0f0f0;
}

#status {
    font-size: 1.2em;
    font-weight: bold;
}

button {
    padding: 10px 20px;
    font-size: 1em;
}
