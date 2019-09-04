Week 2 - Answers


## Student Challenge - Answers ##

### 1: 2 Column layout with Flexbox ###


  ```css

  .row {
  	display: flex;
  	flex-direction: row;
  	flex-wrap: wrap;
  	width: 100%;
  }

  .column {
  	display: flex;
  	flex-direction: column;
  	flex-basis: 100%;
  	flex: 1;
  }

  ```

### 2. Button ###

```css

.btn {
  background-color: #32A952;
	-moz-border-radius: 12px;
	-webkit-border-radius: 12px;
	border-radius: 12px;
	border: 1px solid #2FA74D;
	cursor: pointer;
	color: #FFFFFF;
	font-family: sans-serif;
	font-size: 1.25em;
	font-weight: bold;
	padding: 0.5em 1em;
	text-decoration: none;
	text-transform: uppercase;
	width: 100%;
	max-width: 300px;
	text-align: center;
	display: block;
}

.btn:hover {
	background-color: #288641;
}

```

### 3. Hero background ###

```css

.hero {
	background-color: #171717;
	background: url('../img/hero-background.jpg');
	background-repeat: no-repeat;
	background-position: center;
	background-size: cover;
	color: #FFFFFF;
	padding: 4em 2em;
}

```




Week 3 - Answers

## Student Challenge - Answers ##

### 1:  ###

```HTML

<!-- Link to External Google font -->
<link href="https://fonts.googleapis.com/css?family=Ubuntu:300,300i,400,400i,500,500i,700,700i&display=swap" rel="stylesheet">

```

```CSS

body {
  font-family: 'Ubuntu', sans-serif;
}

```

### 2: Features Group Items ###

Tablet Media Query:

```CSS

.features-item {
  flex-direction: row;
}

.features-item-txt,
.features-item-img {
  align-self: center;
  flex: 1;
}

.features-item-txt {
  padding-left: 2em;
}

```

Desktop Media Query:

```CSS

.features-item {
  flex-direction: row;
}

.features-item:nth-of-type(odd) {
  flex-direction: row-reverse;
}

.features-item-txt,
.features-item-img {
  align-self: center;
}

.features-item-txt {
  padding: 0 2em;
  flex: 1;
}

```

### 3: Badges ###

```HTML

<div class="badges">

  <a href="#"><img src="img/app-store-badge.png" alt="Download on the App Store badge" /></a>

  <a href="#"><img src="img/play-store-badge.png" alt="Get it on Google Play badge" /></a>

</div>

```

```CSS

.badges {
	margin-top: 3em;
	padding: 0;
	text-align: center;
}

```



Week 4 - Answers


## Student Challenge - Answers ##

### 1: Footer ###

```CSS

/* Footer */

footer {
	font-size: 0.8em;
	background: #AE1347;
	color: #FFFFFF;
	padding: 3em 0 0;
}

footer h4 {
	text-transform: uppercase;
}

footer address {
	font-style: normal;
}

.ftr-grid {
	display: grid;
	grid-template-rows: auto;
	grid-row-gap: 1em;
	padding: 0 2em;
}

```
Desktop Media Query:

```CSS

.ftr-grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  column-gap: 1em;
}

```

### 2: Navigation ###

```HTML

Check master branch for solutions with CSS/JS

```

### 3: Accessibility ###

```HTML

Please discuss accessibility.

```




