function createFakeLag(duration) {
    const start = Date.now();
    while (Date.now() - start < duration) {}
}

createFakeLag(5000);

document.body.innerHTML = "<h1>Trang đã tải!</h1>";
