# api-addr
fetch('https://raw.githubusercontent.com/luobinquanbe/api-addr/main/encrypted_config.json')

  .then(r => r.json())

  .then(data => decrypt(data)); // 你实现的解密函数
