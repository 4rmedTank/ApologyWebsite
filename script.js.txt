const messages = [
    "I know I messed up, and I want to make things right. Please accept my heartfelt apology.",
    "I’m truly sorry for what happened. I hope we can move past this and make things better.",
    "I Love you so much, you are my favourite person ever and i value you deeply and Your feelings matter a lot to me.",
];

document.getElementById('changeMessage').addEventListener('click', () => {
    const randomIndex = Math.floor(Math.random() * messages.length);
    document.getElementById('message').textContent = messages[randomIndex];
});

document.getElementById('sendGift').addEventListener('click', () => {
    alert('Sending a virtual gift...');
    // You can add more functionality here, like redirecting to a gift selection page
});
