# TurboTasks
## Задачи для начиниющих и не очень программистов

<details>
	<summary>
		<h2>Легкий уровень</h2>
	</summary>
	<ul>
		<li>
			<details>
				<summary>Игра "больше меньше".</summary>
				<p>Загадывается число от 1 до 1000, задача игрока - угадать число за 10 попыток</p>
			</details>
		</li>
		<li>
			<details>
				<summary>Подсчет "дырочек" в тексте.</summary>
				<p>Например в слове "Windows" - 2 дырочки, а в слове "Linux" - 0 дырочек</p>
			</details>
		</li>
		<li>
			<details>
				<summary>Приложение заменяющие все "Л" на "Р" в тексте, (анимезиция).</summary>
				<p>Компилятор сломался -> Компирятор сромарся.</p>
			</details>
		</li>
		<li>
			<details>
				<summary>Другие задачи</summary>
				<p> Задачи <a href="http://pascalabc.net/downloads/Books/Rubantsev/InterestProjProjects.pdf">отсюда</a>,
					<a href="http://pascalabc.net/downloads/Books/Rubantsev/InterestLessPas.pdf">отсюда</a>, <a
						href="http://pascalabc.net/downloads/Books/Rubantsev/InterestProjProjects.pdf">отсюда</a>, <a
						href="http://pascalabc.net/downloads/Books/Rubantsev/SFML.pdf">отсюда</a>
				</p>
				<p><a href="http://ptaskbook.com/ru">1000 задач</a></p>
				<p><a href="http://algolist.ru">Задачи/алгоритмы</a></p>
			</details>
		</li>
	</ul>
</details>

<details>
	<summary>
		<h2>Средний уровень</h2>
	</summary>
	<ul>
		<li>
			<p> Нормальные крестики-нолики.</p>
		</li>
		<li>
			<p> Игра "Жизнь Конвея".</p>
		</li>
		<li>
			<p> Размытие картинок алгоритмом Box Blur.</p>
		</li>
		<li>
			<p> Рисовалка типа "Paint".</p>
		</li>
		<li>
			<p> Игра "Змейка".</p>
		</li>
		<li>
			<p> Игра "Тетрис".</p>
		</li>
		<li>
			<details>
				<summary>Telegram-bot для подсчета "дырочек" в тексте.</summary>
				<p>Например в слове "Windows" - 2 дырочки, а в слове "Linux" - 0 дырочек</p>
			</details>
		</li>
	</ul>
</details>

<details>
	<summary>
		<h2>Сложный уровень</h2>
	</summary>
	<ul>
		<li>
			<p>Птичка типа "Flappy Bird".</p>
		</li>
		<li>
			<p>Игра 2048.</p>
		</li>
		<li>
			<p>Игра Сапёр.</p>
		</li>
		<li>
			<details>
				<summary>Подсчет "дырочек" в тексте. Усложнённая версия.</summary>
				<p>Подсчёт дырочек должен производиться для произвольных символом
					(Например в слоге "ロ" - 1 дырочка)</p>
			</details>
		</li>
		<li>
			<details>
				<summary>Дизеринг изображений.</summary>
				<p><a href="https://github.com/turborium/Dither3">пример</a></p>
			</details>
		</li>
		<li>
			<details>
				<summary>Приложение заменяющие все "Л" на "Р" в тексте, и озвучивающее
					результат.</summary>
				<p>компилятор сломался -> компирятор
					сромарся <a href="https://github.com/turborium/microsoft-text-to-speech-delphi-example">пример</a>.
				</p>
			</details>
		</li>
	</ul>
</details>
<details>
	<summary>
		<h2>КИБЕРПСИХОЗ🤪 (НЕ СТОИТ)</h2>
	</summary>
	<ul>
		<li>
			<details>
				<summary>Парсер математических выражений вида "4+5*2".</summary>
				<p><a href="https://github.com/turborium/SimpleMathParser">пример</a>.</p>
			</details>
		</li>
		<li>
			<details>
				<summary>Интерпритатор любого языка программирования.</summary>
				<p><a href="https://github.com/turborium/turboriumbasic">пример</a>.</p>
			</details>
		</li>
	</ul>
</details>
<details>
	<summary>
		<h2>Очень сложно.</h2>
	</summary>
	<ul>
		<li>
			<details>
				<summary>Калькулятор (без готового парсера, скобок и т.д.). Проверяю на стриме.</summary>
				<p>Все уверены, что написать простейший калькулятор - очень просто.
					Однако просмотр ютуб роликов вида "пишем калькулятор на языке xxx" показал, что в действительности
					написать хороший, не
					глючный калькулятор - очень сложно.</p>
				<h3>Условия:</h3>
				<ol type="1">
					<li>Калькулятор должен иметь UI/GUI/графический интерфейс.</li>
					<li>Калькулятор должен быть "простейшим" - никаких eval("1+3\*2") и прочих парсеров
						математических выражений.
						Просто имитация самого дешевого калькулятора. Т.е. после нажатия [1] [+] [3] [\*]
						[2] [=] должно получиться 8, а не 7.</li>
					<li>Язык/среда и т.д. - любые.</li>
					<li>Желательны следующие функции: +,-,\*,/,корень,очистка,точка,удаление символа.</li>
					<li>Важное уточнение - количество цифр на «экране» должно быть ограниченным, т.е.
						например ввести можно не более 15 цифр.
						Не должен происходить переход в форму вида 2.43847e16 при вводе большего количества
						цифр.</li>
				</ol>
				<h3>Критерии оценки:</h3>
				<p>Главное: не глючность.
					Не главное: качество кода.</p>
				</p>
			</details>
		</li>
	</ul>
</details>
<hr />
<details>
	<summary>
		<h3>Список выполненных задач.</h3>
	</summary>
	<ul>
		<li>
			<details>
				<summary>Подсчет "дырочек" в тексте.</summary>
				<ul>
					<li> https://github.com/ketchuup/Holes</li>
					<li> https://github.com/Fikerus/holes</li>
					<li> https://gist.github.com/rprtr258/ae549c12fbcbb7c70542ec3a8d4072a8</li>
					<li> https://github.com/osennij-morok/dyrochki (+)</li>
					<li> https://github.com/ketchuup/Holes</li>
				</ul>
			</details>
		</li>
		<li>
			<details>
				<summary>Подсчёт "дырочек" в произвольном тексте.</summary>
				<ul>
					<li> https://github.com/ketchuup/Any (+/-)</li>
					<li> https://github.com/Fikerus/holes-canvas (+)</li>
				</ul>
			</details>
		</li>
		<li>
			<details>
				<summary>Приложение заменяющие все "Л" на "Р" в тексте.</summary>
				<ul>
					<li>https://github.com/BohdanLiuisk/kal-prilozhenie/blob/main/Program.cs</li>
				</ul>
			</details>
		</li>
		<li>
			<details>
				<summary>Приложение заменяющие все "Л" на "Р" в тексте с озвучкой.</summary>
				<ul>
					<li>https://github.com/LeenzeryDev/Animezator/</li>
					<li>https://github.com/cloudlyhimo/tts_repl_py</li>
				</ul>
			</details>
		</li>
		<li>
			<details>
				<summary>Игра "Змейка".</summary>
				<p>https://github.com/rolexxxandr/snake-pygame</p>
			</details>
		</li>
		<li>
			<details>
				<summary>Игра "Жизнь Конвея".</summary>
				<p>https://github.com/rolexxxandr/conways-game</p>
			</details>
		</li>
		<li>
			<details>
				<summary>Telegram-bot для подсчета "дырочек" в тексте.</summary>
				<p>https://github.com/rolexxxandr/holes-tgbot</p>
			</details>
		</li>
</details>
