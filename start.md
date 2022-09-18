# Yeni işletim sistemi başlatılırken yapılacaklar

### Kurulum

- vim-cnf.txt' i .vimrc
- vim-cnf-plg.txt .vimrc.plug:
- olarak kaydet

- Gedit ayarları
- Vim indirilmesi ve konfigrasyonları:
  - $ which vim # vim directory verir
  - vim içerisine :set number numaraları açar (TEK SEFERLİK)
  - vim ~/.vimrc # configleri tutmak için yeni dosya aç
  - bu dosyaya ayarları yazabilirsin
  
- Vim e plugin indirme
  - which curl
  - touch ~/.vimrc.plug
  - içini doldur belirtilengibi
  
  - curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
  
  - : set nonumber numaraları kapatır  
