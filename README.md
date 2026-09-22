<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Velsa Indian Foods</title>
 
<style>
*{
11
margin:0;
padding:0;
box-sizing:border-box;
}
 
body{
font-family:Arial, sans-serif;
background:#f8f8f8;
}
 
header{
background:#0d7a20;
color:white;
padding:20px;
}
  
header h1{
text-align:center;
font-size:40px;
}

header p{
text-align:center;
margin-top:10px;
}

nav{
background:#333;
padding:15px;
text-align:center;
}

nav a{
color:white;
text-decoration:none;
margin:15px;
font-weight:bold;
}

nav a:hover{
color:orange;
}
 
.hero{
text-align:center;
padding:80px 20px;
background:white;
}

.hero h2{
font-size:38px;
color:#0d7a20;
}
 
.hero p{
margin-top:15px;
font-size:18px;
}

.btn{
display:inline-block;
background:#0d7a20;
color:white;
padding:12px 25px;
margin-top:20px;
text-decoration:none;
border-radius:5px;
}

.products{
padding:50px;
text-align:center;
}

.products h2{
color:#0d7a20;
margin-bottom:30px;
}

.product-container{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
}

.card{
background:white;
width:280px;
padding:20px;
border-radius:10px;
box-shadow:0px 0px 10px #ccc;
}

.card img{
width:100%;
height:180px;
object-fit:cover;
border-radius:10px;
}

.card h3{
margin-top:15px;
}

.btn-buy{
background:orange;
color:white;
border:none;
padding:10px 20px;
margin-top:15px;
border-radius:5px;
cursor:pointer;
}

.about{
background:#fff;
padding:60px;
129
text-align:center;
130
}
131
 
132
.about h2{
133
color:#0d7a20;
134
}
135
 
136
.about p{
137
margin-top:20px;
138
line-height:1.8;
139
}
140
 
141
.login{
142
padding:60px;
143
background:#eef7ee;
144
}
145
 
146
.login-box{
147
max-width:400px;
148
margin:auto;
149
background:white;
150
padding:30px;
151
border-radius:10px;
152
box-shadow:0 0 10px #bbb;
153
}
154
 
155
.login-box h2{
156
text-align:center;
157
color:#0d7a20;
158
margin-bottom:20px;
159
}
160
 
161
input{
162
width:100%;
163
padding:12px;
164
margin-bottom:15px;
165
border:1px solid #ccc;
166
border-radius:5px;
167
}
168
 
169
button{
170
width:100%;
171
padding:12px;
172
background:#0d7a20;
173
color:white;
174
border:none;
175
border-radius:5px;
176
cursor:pointer;
177
}
178
 
179
.contact{
180
padding:60px;
181
background:white;
182
text-align:center;
183
}
184
 
185
.contact h2{
186
color:#0d7a20;
187
}
188
 
189
.contact p{
190
margin-top:10px;
191
}
192
 
193
footer{
194
background:#222;
195
color:white;
196
text-align:center;
197
padding:20px;
198
}
199
 
200
</style>
201
 
202
<script>
203
 
204
function sendOTP()
205
{
206
var mobile = document.getElementById("mobile").value;
207
 
208
if(mobile.length != 10)
209
{
210
alert("Please enter valid mobile number");
211
return;
212
}
213
 
214
alert("OTP Sent Successfully to " + mobile);
215
}
216
 
217
function verifyOTP()
218
{
219
var otp = document.getElementById("otp").value;
220
 
221
if(otp.length != 6)
222
{
223
alert("Invalid OTP");
224
return;
225
}
226
 
227
alert("Login Successful");
228
}
229
 
230
</script>
231
 
232
</head>
233
 
234
<body>
235
 
236
<header>
237
<h1>Velsa Indian Foods</h1>
238
<p>Pure & Trusted Food Products for Every Home</p>
239
</header>
240
 
241
<nav>
242
#Home</a>
243
#productsProducts</a>
244
#aboutAbout Us</a>
245
#loginLogin</a>
246
#contactContact</a>
247
</nav>
248
 
249
<section class="hero">
250
<h2>Welcome to Velsa Indian Foods</h2>
251
<p>Premium Coconut Oil, Groundnut Oil, Rice and Daily Essential Food Products.</p>
252
#productsView Products</a>
253
</section>
254
 
255
<section class="products" id="products">
256
 
257
<h2>Our Products</h2>
258
 
259
<div class="product-container">
260
 
261
<div class="card">
262
https://via.placeholder.com/280x180
263
<h3>Coconut Oil</h3>
264
<p>100% Pure Coconut Oil for healthy cooking.</p>
265
<button class="btn-buy">Buy Now</button>
266
</div>
267
 
268
<div class="card">
269
https://via.placeholder.com/280x180
270
<h3>Groundnut Oil</h3>
271
<p>Fresh and healthy traditional groundnut oil.</p>
272
<button class="btn-buy">Buy Now</button>
273
</div>
274
 
275
<div class="card">
276
https://via.placeholder.com/280x180
277
<h3>Premium Rice</h3>
278
<p>Excellent quality rice for your family.</p>
279
<button class="btn-buy">Buy Now</button>
280
</div>
281
 
282
</div>
283
 
284
</section>
285
 
286
<section class="about" id="about">
287
 
288
<h2>About Velsa Indian Foods</h2>
289
 
290
<p>
291
Velsa Indian Foods provides high-quality food products including
292
Coconut Oil, Groundnut Oil, Rice, Pulses, and other grocery items.
293
Our mission is to deliver healthy and trusted food products to every home.
</p>

</section>
<section class="login" id="login">
  
<div class="login-box">
<h2>Customer Login</h2>
  
<input type="text"
id="mobile"
placeholder="Enter Mobile Number">

<button onclick="sendOTP()">
Send OTP
</button>
<br><br>

<input type="text"
id="otp"
placeholder="Enter OTP">

<button onclick="verifyOTP()">
Verify OTP & Login
</button>
</div>
</section>
<section class="contact" id="contact">
<h2>Contact Us</h2>

<p><b>Velsa Indian Foods</b></p>
<p>Email: info@velsindianfoods.com</p>
<p>Phone: +91 9876543210</p>
<p>Tamil Nadu, India</p>
  
</section>

<footer>
© 2026 Velsa Indian Foods. All Rights Reserved.
</footer>
  
</body>
342
</html>
