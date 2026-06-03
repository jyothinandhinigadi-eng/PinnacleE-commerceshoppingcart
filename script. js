let total = 0;

function addToCart(productName, price) {

    const cartItems = document.getElementById("cart-items");

    const li = document.createElement("li");
    li.textContent = `${productName} - ₹${price}`;

    cartItems.appendChild(li);

    total += price;

    document.getElementById("total").textContent = total;
}

function clearCart() {

    document.getElementById("cart-items").innerHTML = "";

    total = 0;

    document.getElementById("total").textContent = total;
}
