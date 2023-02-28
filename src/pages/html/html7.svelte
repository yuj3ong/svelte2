<style>
	.viewer {
		display: flex;
		flex-direction: column;
	}

	.head,
	.body,
	.footer {
		display: flex;
	}

	.head {
		justify-content: space-between;
	}

	.topButton {
		display: flex;
	}

	.topButton ul {
		display: flex;
		flex-direction: row;
		justify-content: flex-start;
	}
</style>

<main>
	<div class="viewer">
		<!-- <head>, <body>, <footer> stack -->
		<div class="head">
			<!--  -->
			<div class="topButton">
				<ul>
					<li>
						<ul class="btnBundle">
							<li id="icon1">icon1</li>
							<li>icon2</li>
						</ul>
					</li>

					<li>
						<ul class="btnBundle">
							<li>icon3</li>
							<li>icon4</li>
						</ul>
					</li>

					<li>
						<ul class="btnBundle">
							<li>icon3</li>
							<li>icon4</li>
						</ul>
					</li>

					<li>
						<ul class="btnBundle">
							<li>icon3</li>
							<li>icon4</li>
						</ul>
					</li>

					<li>
						<ul class="btnBundle">
							<li>icon3</li>
							<li>icon4</li>
						</ul>
					</li>
				</ul>
			</div>
			<!--  -->
			<div class="topTimetable">
				<div class="topRealtime">
					<p>Realtime:2023-02-28 17:20:25</p>
				</div>
				<div class="topClock">
					<p>topRighticon</p>
				</div>
			</div>
		</div>
		<!--  -->
		<div class="body">
			<div class="sideTab">
				<div class="hostTab">
					<ul>
						<li>host</li>
						<li>groups</li>
						<li>VMWares</li>
						<li>VMWareGroups</li>
						<li>Xens</li>
					</ul>
				</div>
				<div class="treeIcon">
					<ul>
						<li>
							<ul>
								<li>tree1</li>
								<li>tree2</li>
							</ul>
						</li>

						<li>
							<ul>
								<li>tree3</li>
								<li>tree4</li>
								<li>tree5</li>
							</ul>
						</li>
					</ul>
				</div>
				<div class="hostTree"></div>
			</div>

			<div class="chartTab"></div>
		</div>
		<!--  -->
		<div class="footer">
			<div class="hostCount">
				<p>57 host(s) Selected</p>
			</div>
			<div class="connectOn">
				<p><span>bottomIcon1</span>50</p>
			</div>
			<div class="connectOff">
				<p><span>bottomIcon2</span>27</p>
			</div>
			<div class="bottomRealtime">
				<p><span>bottomIcon3</span>2023-02-28 17:20:25</p>
			</div>
		</div>
		<!--  -->
	</div>
</main>
