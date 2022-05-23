<script>
	import "nes.css/css/nes.min.css";
	export let name;
	import Typewriter from  "svelte-typewriter";
</script>

<main>
		
			
	
	<Typewriter scramble>
		<h1>Hello World</h1>	
		<h2>南臺科技大學</h2>
		<p>
			Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
			how to build Svelte apps.
		</p>
	</Typewriter>		
	
	<div class="nes-container with-title " style="text-align:left">
		<p style="font-size:x-large" class="title">校訓</p>
		<p>		
			<Typewriter interval={80}>
				南臺科技大學的校訓是在約40年前(1969年)由首任校長辛文炳先生制定。當時南臺剛成立，全名是私立南臺工業實用技藝專科學校。
				校長文炳先生與吳修齊、吳尊賢、張麗堂…等先生同是學校的創辦人。他在南臺當了20年的校長(1969~1989)，10年的董事長(1989~1999)，於南臺任職的30年間文炳先生不但未領分毫薪水、不設工友值役，很多公務上的花費還自掏腰包，甚至捐獻現在的師生活動中心─文炳館與西淮紀念館，是令人懷念敬重的一位長者。
				1999年出版的「世間最幸福的人─辛文炳先生、辛翁梅女士賢伉儷鑽石婚紀念集」中，提到文炳先生留日時期對法學的體會，他說：『信義誠實』是我在日本讀書所看到的，也認為這是與人相處最重要的原則，從學習的眾多科目中，經濟學也好，公平法也好，實際上都是這四個字就能解決。』這位為南臺奉獻自己的老先生讓這四個字成為自己一生的行事風格，更殷殷期盼的將它制定成南臺的校訓，期許南臺培育出的學生也能擁有這美好的品德。
			</Typewriter>
		</p>
	</div>

	<br />
	
	<div style="margin-top:10px">
		<button style="width:100px" class="nes-btn is-primary">確定</button>
		<button style="width:100px" class="nes-btn is-warning">取消</button>
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
