# velsindianfoods
velsindianfoods products

<!DOCTYPE html>
2
<html lang="en">
3
<head>
4
<meta charset="UTF-8">
5
<meta name="viewport" content="width=device-width, initial-scale=1.0">
6
<title>Velsa Indian Foods</title>
7
 
8
<style>
9
 
10
*{
11
margin:0;
12
padding:0;
13
box-sizing:border-box;
14
}
15
 
16
body{
17
font-family:Arial, sans-serif;
18
background:#f8f8f8;
19
}
20
 
21
header{
22
background:#0d7a20;
23
color:white;
24
padding:20px;
25
}
26
 
27
header h1{
28
text-align:center;
29
font-size:40px;
30
}
31
 
32
header p{
33
text-align:center;
34
margin-top:10px;
35
}
36
 
37
nav{
38
background:#333;
39
padding:15px;
40
text-align:center;
41
}
42
 
43
nav a{
44
color:white;
45
text-decoration:none;
46
margin:15px;
47
font-weight:bold;
48
}
49
 
50
nav a:hover{
51
color:orange;
52
}
53
 
54
.hero{
55
text-align:center;
56
padding:80px 20px;
57
background:white;
58
}
59
 
60
.hero h2{
61
font-size:38px;
62
color:#0d7a20;
63
}
64
 
65
.hero p{
66
margin-top:15px;
67
font-size:18px;
68
}
69
 
70
.btn{
71
display:inline-block;
72
background:#0d7a20;
73
color:white;
74
padding:12px 25px;
75
margin-top:20px;
76
text-decoration:none;
77
border-radius:5px;
78
}
79
 
80
.products{
81
padding:50px;
82
text-align:center;
83
}
84
 
85
.products h2{
86
color:#0d7a20;
87
margin-bottom:30px;
88
}
89
 
90
.product-container{
91
display:flex;
92
flex-wrap:wrap;
93
justify-content:center;
94
gap:20px;
95
}
96
 
97
.card{
98
background:white;
99
width:280px;
100
padding:20px;
101
border-radius:10px;
102
box-shadow:0px 0px 10px #ccc;
103
}
104
 
105
.card img{
106
width:100%;
107
height:180px;
108
object-fit:cover;
109
border-radius:10px;
110
}
111
 
112
.card h3{
113
margin-top:15px;
114
}
115
 
116
.btn-buy{
117
background:orange;
118
color:white;
119
border:none;
120
padding:10px 20px;
121
margin-top:15px;
122
border-radius:5px;
123
cursor:pointer;
124
}
125
 
126
.about{
127
background:#fff;
128
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
294
</p>
295
 
296
</section>
297
 
298
<section class="login" id="login">
299
 
300
<div class="login-box">
301
 
302
<h2>Customer Login</h2>
303
 
304
<input type="text"
305
id="mobile"
306
placeholder="Enter Mobile Number">
307
 
308
<button onclick="sendOTP()">
309
Send OTP
310
</button>
311
 
312
<br><br>
313
 
314
<input type="text"
315
id="otp"
316
placeholder="Enter OTP">
317
 
318
<button onclick="verifyOTP()">
319
Verify OTP & Login
320
</button>
321
 
322
</div>
323
 
324
</section>
325
 
326
<section class="contact" id="contact">
327
 
328
<h2>Contact Us</h2>
329
 
330
<p><b>Velsa Indian Foods</b></p>
331
<p>Email: info@velsindianfoods.com</p>
332
<p>Phone: +91 9876543210</p>
333
<p>Tamil Nadu, India</p>
334
 
335
</section>
336
 
337
<footer>
338
© 2026 Velsa Indian Foods. All Rights Reserved.
339
</footer>
340
 
341
</body>
342
</html>
