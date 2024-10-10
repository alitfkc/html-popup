
# HTML Popup

# EN
With this plugin, you can easily add approval and email verification to your transactions.


## Example

```html
<!--popup approval form-->
<div>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname">
    <button onclick="createApprovalPopup('mail','Are you sure?','You will save this form',sendCode)">Send</button>
</div>

<script src="popup.js"></script>

```
```javascript
function sendCode() {
    createMailCodePopup('testmail.com','Verify Code','We have sent a 6 digit verification code for this form',sendForm)
}
function sendForm(code){
    console.log(code)
}

```
# TR
Bu eklenti ile rahatça işlemlerinize  onay ve mail ile doğrulama ekleyebilirsiniz.

## Örnek

```html
<!--popup approval form-->
<div>
    <label for="fname">İsim:</label><br>
    <input type="text" id="fname" name="fname"><br>
    <label for="lname">Soy isim:</label><br>
    <input type="text" id="lname" name="lname">
    <button onclick="createApprovalPopup('mail','Emin misin?','Bu formu kayıt edeceksin!',sendCode)">Send</button>
</div>

<script src="popup.js"></script>

```
```javascript
function sendCode() {
    createMailCodePopup('testmail.com','Onaylama Kodu','Bu form için 6 haneli bir doğrulama kodu gönderdik',sendForm)
}
function sendForm(code){
    console.log(code)
}

```

  

  
## Ekran Görüntüleri

![Uygulama Ekran Görüntüsü](https://github.com/alitfkc/html-popup/blob/main/imgs/img1.png)

  
