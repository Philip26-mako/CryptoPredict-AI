function record(){
 let a=Number(localStorage.getItem("records")||0)+1;
 localStorage.setItem("records",a);
 document.getElementById("records").textContent=a+" demo records";
}
document.getElementById("market").onchange=()=>analyse(tf);
analyse(tf);
</script>
</body>
</html># CryptoPredict-AI
AI- powered cryptocurrency and forex market signals dashboard 
