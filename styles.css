let cart = [];
let total = 0;

function addToCart(productName, price) {
    cart.push({ name: productName, price: price });
    total += price;
    displayCart();
}

function displayCart() {
    const cartItems = document.getElementById("cart-items");
    const totalDisplay = document.getElementById("total");

    cartItems.innerHTML = "";

    cart.forEach(item => {
        let li = document.createElement("li");
        li.textContent = item.name + " - $" + item.price;
        cartItems.appendChild(li);
    });

    totalDisplay.textContent = total;
}

function checkout() {
    if (cart.length === 0) {
        alert("Your cart is empty!");
    } else {
        alert("Order placed successfully! Thank you LTBrown Community!");
        cart = [];
        total = 0;
        displayCart();
    }
}
