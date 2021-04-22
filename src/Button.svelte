<script>
	let count = 0;

	function handleClick() {
	  count += 1;
	}
</script>

<style>
	#filers-css-generator-demo {
filter: brightness(85%) saturate(484%) contrast(86%) drop-shadow(81px 162px 94px #332c2c);
-webkit-filter: brightness(85%) saturate(484%) contrast(86%) drop-shadow(81px 162px 94px #332c2c);
-moz-filter: brightness(85%) saturate(484%) contrast(86%) drop-shadow(81px 162px 94px #332c2c);
	}
	button {
	  background: #ff3e00;
	  color: white;
	  border: 15px solid #1c6ea4;
	  padding: 8px 12px;
	  border-radius: 2px;
	}
</style>
<div id="filer-css-generator-demo" style="">
<button on:click={handleClick}>
  Clicked {count} {count === 1 ? 'time' : 'times'}
</button>
        </div>
<div id="filers-css-generator-demo">
          <img src="https://cssgenerator.org/images/img_for_filter.jpg" alt="Demo Image for Filter CSS Effects">
        </div>