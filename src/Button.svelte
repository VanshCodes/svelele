<script>
	export let counts = 0;

	function handleClick() {
	  counts += 1;
	}
</script>

<style>
                button {
                  color: rgb(0, 0, 0);
                  font-size: 19px;
                  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
                    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
                  border: none;

                  /* transition-delay: 100ms; */
                  padding: 8px 12px;
                  background: #000000;
                  /* background-image: -webkit-linear-gradient(top, #000000, #b82b2b);
                                      background-image: -moz-linear-gradient(top, #000000, #b82b2b);
                                      background-image: -ms-linear-gradient(top, #000000, #b82b2b);
                                      background-image: -o-linear-gradient(top, #000000, #b82b2b);
                                      background-image: linear-gradient(to bottom, #000000, #b82b2b); */
                  -webkit-border-radius: 28;
                  -moz-border-radius: 28;
                  border-radius: 8px;
                  font-family: Arial;
                  color: #ffffff;
                  font-size: 20px;
                  padding: 10px 20px 10px 20px;
                  text-decoration: none;
                  transition: all 0.5s linear;
                  -moz-transition: all 0.5s linear; /* Firefox 4 */
                  -webkit-transition: all 0.5s linear; /* Safari and Chrome */
                  -o-transition: all 0.5s linear; /* Opera */
                  -ms-transition: all 0.5s linear; /* Explorer 10 */
                  /* transition: all 100ms linear 10s; */
                  /* transition-property: all;
                                              transition-duration: 10s;
                                              transition-timing-function: linear; */
                }
                button:hover {
                  background: #fe5f00;

                  /* filter: brightness(80%); */
                  /* background: #e016e0;
                                            background-image: -webkit-linear-gradient(top, #e016e0, #2c3fb8);
                                            background-image: -moz-linear-gradient(top, #e016e0, #2c3fb8);
                                            background-image: -ms-linear-gradient(top, #e016e0, #2c3fb8);
                                            background-image: -o-linear-gradient(top, #e016e0, #2c3fb8);
                                            background-image: linear-gradient(to bottom, #e016e0, #2c3fb8); */
                  /* -webkit-border-radius: 28;
                                            -moz-border-radius: 28; */
                  /* border-radius: 28px;
                                            font-family: Arial;
                                            color: #ffffff;
                                            font-size: 20px;
                                            padding: 10px 20px 10px 20px;
                                            text-decoration: none; */

                  /* width: 50%; */
                }
</style>

<button on:click={handleClick}>
  Clicked {counts} {counts === 1 ? 'time' : 'times'}
</button>