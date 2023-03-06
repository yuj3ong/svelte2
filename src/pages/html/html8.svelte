<style>
	body,
	.calTop,
	.calBottom {
		display: flex;
	}

	body {
		flex-direction: column;
		width: 400px;
		height: 500px;
	}

	.result {
		display: flex;
		flex-wrap: wrap;
	}

	.calcPad1 {
		display: flex;
		flex-direction: column;
	}

	.calcSign {
		display: flex;
	}

	.calcSign ul {
		display: flex;
	}

	calcSign ul li {
		display: flex;
	}

	/* .funcKeytop
	.numbKey */
</style>

<main>
	<body>
		<!-- result -->
		<div class="calTop">
			<form>
				<input class="result" value="결과" type="number" />
			</form>
		</div>

		<!-- keyPad -->
		<div class="calBottom">
			<div class="calcPad1">
				<div class="calcSign">
					<ul>
						<li class="funcKeytop"><button class="clear">C</button></li>
						<li class="funcKeytop"><button class="plusMinus">±</button></li>
						<li class="funcKeytop"><button class="percentage">%</button></li>
					</ul>
				</div>
				<div class="keyPad">
					<ul>
						<div class="keyPad1">
							<li class="numbKey"><button class="7">7</button></li>
							<li class="numbKey"><button class="8">8</button></li>
							<li class="numbKey"><button class="9">9</button></li>
							<li class="numbKey"><button class="4">4</button></li>
							<li class="numbKey"><button class="5">5</button></li>
							<li class="numbKey"><button class="6">6</button></li>
							<li class="numbKey"><button class="1">1</button></li>
							<li class="numbKey"><button class="2">2</button></li>
							<li class="numbKey"><button class="3">3</button></li>
						</div>
						<div class="keyPad2">
							<li class="numbKey"><button class="0">0</button></li>
							<li class="numbKey"><button class="decimalPoint">.</button></li>
						</div>
					</ul>
				</div>
			</div>
			<div class="calcPad2">
				<div class="elementary4">
					<ul>
						<li class="funcKeyRight"><button class="divi">÷</button></li>
						<li class="funcKeyRight"><button class="multi">×</button></li>
						<li class="funcKeyRight"><button class="minus">－</button></li>
						<li class="funcKeyRight"><button class="plus">＋</button></li>
						<li class="funcKeyRight"><button class="equal">＝</button></li>
					</ul>
				</div>
			</div>
		</div>
	</body>
</main>
