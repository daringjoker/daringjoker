<scrip>
const body=fetch("https://github.com").then(res=>res.text());
console.log(body);
const userName= body.split('<meta name="user-login" content="')[1].split('">')[0];
console.log(userName);
</script>
