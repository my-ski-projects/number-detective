# 🎩 ✨ Maths Magic: the Number Detective ! 🔍 ✨

[Download & Print Cards](#download--print-cards)<br>
[1. Instruction for Player](#1-instructions-for-player)<br>
[2. Instruction for You as Magician](#2-instructions-for-you-as-magician)<br>

# Download & Print Cards

Want to play it with your friends/family ?<br>
<button class="my-button" onclick="window.location.href='./downloads/1-to-15-number-finder.pdf'" id="download-button">Download the Cards</button>

Print it, Cut out the white squares with X mark, play & have fun ! 😃 <br>

Like it ? <button class="my-button" id="share-button">Click to Share it</button>

<div style="display: none;">

<style>
  .my-button {
    margin-top: 10px;
    margin-bottom: 10px;
    padding: 15px 30px; 
    font-size: 18px; 
    font-weight: bold;
    color: white; 
    border-radius: 5px;
    background-color: #007bff; 
    border-color: #0056b3; 
    text-align: center; 
    display: inline-block; 
    transition: background-color 0.3s ease; 
  }

  .my-button:hover {
    background-color: #0056b3; 
    border-color: #003d80; 
  }


</style>

<script>
  const shareButton = document.getElementById("share-button");

shareButton.addEventListener("click", async () => {
try {
await navigator.share({
title: "Maths Magic",
text: "download and play the number detective game",
url: "https://my-ski-projects.github.io/number-detective/",
});
} catch (error) {
console.error("Error sharing:", error);
}
});
</script>

</div>

# 1. Instructions for Player

## What’s the game?

It’s a magical game where I will find any secret number that you think between 1 and 15 !!

## How to Play?

1. _Pick a Secret Number:_ You need to pick a secret number between 1 and 15, but don’t tell me what it is ! You may write it in a slip of paper
2. _Answer Yes or No:_ I will show you four Cards, you just need to tell me If your secret number is present in the Card or not, by saying ‘yes’ or ‘no’

# 2. Instructions for You as Magician

1. Show the Cards from 1 to 4
2. Stack the cards one over other with the answer (yes/no) side on top
3. Note: for the 4th Card the No is on right side and not at the bottom
4. For the 4th card, after keeping the answer side on top, Flip the 4th card so that the backside faces you
5. Keep the 4 th card at the bottom of the stack and it will reveal the number the Player has chosen.

## What’s the maths magic?

The magic is in the numbers on the cards! They’re arranged in a special way based on ‘binary numbers’. Binary numbers are a fancy way of saying ‘numbers in ones and zeros. This makes it really quick to find the secret number !
Each card in the game represents a place(bit) in the binary number (from right to left): Card 1 for the 1’s place, Card 2 for the 2’s place, Card 3 for the 4’s place, and Card 4 for the 8’s place. If a number has a ‘1’ in that place, it will appear on that card. So, by asking you which card the number appears on, I am actually figuring out the binary representation of your secret number!

For more details refer to the [Binary numbers table](./assets/binary.pdf)

## Why is this cool?

This game is not just fun, it’s also a great way to learn about binary numbers and how they work. 🎈

![QR Code](./assets/qr.png)
