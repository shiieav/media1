<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <title>Survey</title>
    <styles>
    body {
      width: 100%;
      height: 100vh;
      margin: 0;
      background-color: #1b1b44;
      color: #e5e1ef;
      font-family: Tahoma;
      font-size: 18px;
    }

h1, p, h2 {
  margin: 1em auto;
  text-align: center;
}

p {
  font-size: 5px;
  color: #e5e1ef;
}

h2 {
font-family:'Oswald', sans-serif;
font-size: 13px;
color: #e5e1ef;
font-style: italic;
  }

h3 {
font-family: 'Oswald', sans-serif;
font-size: 20px;
  }

h4 {
  font-family: 'Oswald', sans-serif;
  font-size: 10px;
  font-style: italic;
  }

.img {
width: 200px; 
height: auto;
max-width: 100%;
margin: 1em;
  }

form {
  width: 60vw;
  max-width: 500px;
  min-width: 300px;
  margin: 0 auto;
  padding-bottom: 2em;
  background-color: #1b1b44;
  font-size: 20px;
}

fieldset {
  border: none;
  padding: 2rem 0;
  border-bottom: 3px solid #1b1b44;
}

fieldset:last-of-type {
  border-bottom: none;
}

label {
  display: block;
  margin: 0.5rem 0;
}

input,
textarea,
select {
  margin: 10px 0 0 0;
  width: 100%;
  min-height: 2em;
}

input, textarea {
  background-color: #0a0a23;
  border: 1px solid #0a0a23;
  color: #ffffff;
}

.container {
  margin: 0 auto;
  width: 500px;
  max-width: 1100px;  
}

.container  {
    width: 500px;
    background-color: #1b1b44;
    margin: 0 auto;
    padding: 1em 0;
    color: #f2f2f2;
  }

#description {
  line-height: 1.5em;
  margin-top: 1em;
}

.Kyougen, .utanouta, .Campanella, .Utattemita {
  width: 270px;
  margin: 40px auto 0 auto;
  padding: 15px 0 15px 0;
  size: 50px;
}

.inline {
  width: unset;
  margin: 0 0.5em 0 0;
  vertical-align: middle;
}

input[type="submit"] {
  display: block;
  width: 60%;
  margin: 1em auto;
  height: 2em;
  font-size: 1.1rem;
  background-color: #3b3b4f;
  border-color: white;
  min-width: 300px;
}

input[type="file"] {
  padding: 1px 2px;
}

.inline{
  display: inline; 
}

a {
  color: #dfdfe2;
}

input[type="radio"] {
  transition: border-color 0.2s ease-in-out;
}

input[type="radio"]:checked {
  border-color: #3b3b4f;
}

    </styles>
</head>

<body>
    <center>
        <div class="heading">
            <div class="container">
                                <p id="description">This is a fanmade survey.</p>
                <h1 id="title">Ado Survey</h1>
                <h2 id="sub-title">If God is left handed, I can’t imagine how happy I’ll be.</h2>
                <a href="https://twitter.com/ado1024imokenp"><img class="img"
                        src="https://static.utaitedb.net/img/artist/mainThumb/23501.jpg?v=3" alt="airplane-flying"></a>
            </div>
        </div>
    </center>
        <form id="survey-form">
            <fieldset>
                <label for="name" id="name-label">Name :<input type="text" class="personal-info__data" id="name"name="name" placeholder="Enter your name" required /></label>
                <label for="email" id="email-label">Email :<input type="email" class="personal-info__data" id="email"name="email" placeholder="Enter your email" required /></label>
                <label for="number" id="number-label">Age :<input type="number" class="personal-info__data" id="number" name="age" min="10" max="115" placeholder="Enter your age" required /></label>
            </fieldset>

            <div class="container">
                <h3>When did you became an Ado Fan?</h3>
                <select id="dropdown" name="Ado Fan">
                    <option value="select">[Select one]</option>
                    <option value="2017">2017</option>
                    <option value="2018">2018</option>
                    <option value="2019">2019</option>
                    <option value="2020">2020</option>
                    <option value="2021">2021</option>
                    <option value="2022">2022</option>
                    <option value="2023">2023</option>
                    <option value="2024">2024</option>
                </select>
            </div>
        </div>
    </div>
            <div class="container">
                <h3>Which Ado album is your favorite?</h3>
                <select id="album" name="album">
                    <option value="select">[Select one]</option>
                    <option value="bc">Kyougen</option>
                    <option value="ab">Uta no Uta ONE PIECE FILM RED</option>
                    <option value="sk">Campanella</option>
                    <option value="mb">Ado no Utattemita</option>
                </select>
            </div>
        </div>


        <div class="container">
                <fieldset>
                    <legend>
                        <h3>Before you proceed, we want to know how much you love Ado-san.</h3>
                    </legend>
                        <label for="rm"><input type="radio" class="inline" name="new-options" id="rm" value="rm"> "Mid."</label>
                        <label for="odo"><input type="radio" class="inline" name="new-options" id="odo" value="odo"> "I like her!"</label>
                        <label for="ddv"><input type="radio" class="inline" name="new-options" id="ddv" value="ddv"> "I so love her!"</label>
                        <label for="freedom"><input type="radio" class="inline" name="new-options" id="freedom" value="freedom"> "Just here for the song."</label>
                        <label for="fw"><input type="radio" class="inline" name="new-options" id="fw" value="fw"> "I love everything about her!"</label>
                        <label for="ai"><input type="radio" class="inline" name="new-options" id="ai" value="ai"> "SHE IS AN ANGEL! WAIT, NO! A GODDESS!!! HER SCREAMS PURIFIES MY SOUL! I LOVE HOW MYSTERIOUS SHE IS AND NO MATTER WHAT KIND OF AN UTAITE/ARTIST SHE BECOME, I WILL ALWAYS SUPPORT HER!!! NO ADO, NO LIFE!!! I STAND FOR ADOMINATION!!!"</label>
                </fieldset>
        </div>

            <div class="container">
                <h4>You can choose how many you like, there is no limit. Enjoy~</h4>
            </div>
        </div>

        <div class="container">
            <a href="https://www.cdjapan.co.jp/product/TYCT-69203"><img class="Kyougen"src="https://th.bing.com/th/id/R.e6f5220e0bfdb177ff7fc3924b282b76?rik=1O2KsbI37j5TVQ&riu=http%3a%2f%2fst.cdjapan.co.jp%2fpictures%2fl%2f02%2f39%2fTYCT-69205.jpg&ehk=CzoJHqvzwN2emARjkDKI2jl7ZggjZ4CyhKvwOHsVL1k%3d&risl=&pid=ImgRaw&r=0"alt="Kyougen"></a>
                <fieldset>
                    <legend>
                        <h3>Which track in Kyougen is your favorite?</h3>
                    </legend>
                        <label for="rm"><input type="checkbox" class="inline" name="new-options" id="rm" value="rm"> "Readymade" (レディメイド)</label>
                        <label for="odo"><input type="checkbox" class="inline" name="new-options" id="odo" value="odo"> "Odo" (踊)</label>
                        <label for="ddv"><input type="checkbox" class="inline" name="new-options" id="ddv" value="ddv"> "Domestic De Violence"(ドメスティックでバイオレンス)</label>
                        <label for="freedom"><input type="checkbox" class="inline" name="new-options" id="freedom" value="freedom"> "Freedom"</label>
                        <label for="fw"><input type="checkbox" class="inline" name="new-options" id="fw" value="fw"> "Fireworks" (花火)</label>
                        <label for="ai"><input type="checkbox" class="inline" name="new-options" id="ai" value="ai"> "Aitakute" (会いたくて)</label>
                        <label for="lb"><input type="checkbox" class="inline" name="new-options" id="lb" value="lb"> "Lucky Bruto" (ラッキー・ブルート)</label>
                </fieldset>
                <fieldset>
                    <legend>
                        <h3>Which track in Kyougen is your favorite? [pt.2]</h3>
                    </legend>
                        <label for="gg"><input type="checkbox" class="inline" name="new-options" id="gg" value="gg"> "Gira Gira" (ギラギラ)</label>
                        <label for="ac"><input type="checkbox" class="inline" name="new-options" id="ac" value="ac"> "Ashura-chan" (阿修羅ちゃん)</label>
                        <label for="ktinnf"><input type="checkbox" class="inline" name="new-options" id="ktinnf" value="ktinnf"> "Kokoro to iu Na noFukakai" (心という名の不可解)</label>
                        <label for="usseewa"><input type="checkbox" class="inline" name="new-options" id="usseewa" value="usseewa"> "Usseewa" (うっせぇわ)</label>
                        <label for="ml"><input type="checkbox" class="inline" name="new-options" id="ml" value="ml"> "Motherland" (マザーランド)</label>
                        <label for="kaga"><input type="checkbox" class="inline" name="new-options" id="kaga" value="kaga"> "Kagakushu" (過学習)</label>
                        <label for="ynp"><input type="checkbox" class="inline" name="new-options" id="ynp" value="ynp"> "Yoru no Pierrot" (夜のピエロ)</label>
                </fieldset>
        </div>
        <div class="container">
            <a href="https://www.cdjapan.co.jp/product/TYCT-69245"><img class="utanouta" src="https://animatebkk-online.com/wp-content/uploads/2022/06/4988031519660-768x768.jpg"alt="utanouta"></a>
                <fieldset>
                    <legend>
                        <h3>Which track in Uta no Uta ONE PIECE FILM RED is your favorite?</h3>
                    </legend>
                        <label for="ng"><input type="checkbox" class="inline" name="new-options" id="ng" value="ng"> "New Genesis"(新時代)</label>
                        <label for="ii"><input type="checkbox" class="inline" name="new-options" id="ii" value="ii"> "I'm Invincible"(私は最強)</label>
                        <label for="bl"><input type="checkbox" class="inline" name="new-options" id="bl" value="bl"> "Backlight" (逆光)</label>
                        <label for="fl"><input type="checkbox" class="inline" name="new-options" id="fl" value="fl"> "Fleeting Lullaby" (ウタカタララバイ)
                        </label>
                </fieldset>
                <fieldset>
                    <legend>
                        <h3>Which track in Uta no Uta ONE PIECE FILM RED is your favorite? [pt.2]</h3>
                    </legend>
                        <label for="tm"><input type="checkbox" class="inline" name="new-options" id="tm" value="tm"> "Tot Musica"</label>
                        <label for="twc"><input type="checkbox" class="inline" name="new-options" id="twc" value="twc"> "The World's Continuation"(世界のつづき)</label>
                        <label for="wtwb"><input type="checkbox" class="inline" name="new-options" id="wtwb" value="wtwb"> "Where the Wind Blows"(風のゆくえ)</label>
                        <label for="bs"><input type="checkbox" class="inline" name="new-options" id="bs" value="bs"> "Binks' Sake" (ビンクスの酒)
                        </label>
                </fieldset>
        </div>
        <div class="container">
            <a href="https://www.cdjapan.co.jp/product/TYXT-19027"><img class="Campanella"src="https://st.cdjapan.co.jp/pictures/l/15/23/TYBT-19033.jpg?v=1" alt="Campanella"></a>
                <fieldset>
                    <legend>
                        <h3>Which track in Campanella is your favorite?</h3>
                    </legend>
                        <label for="ynp"><input type="checkbox" class="inline" name="new-options" id="ynp" value="ynp" /> "Yoru no Pierrot"(夜のピエロ)</label>
                        <label for="lb"><input type="checkbox" class="inline" name="new-options" id="lb" value="lb"> "Lucky Bruto" (ラッキー・ブルート)</label>
                        <label for="lk"><input type="checkbox" class="inline" name="new-options" id="lk" value="lk"> "Love Ka?" (ラブカ？ 歌いました)</label>
                        <label for="ddv"><input type="checkbox" class="inline" name="new-options" id="ddv" value="ddv"> "Domestic De Violence"(ドメスティックでバイオレンス)</label>
                        <label for="bl"><input type="checkbox" class="inline" name="new-options" id="bl" value="bl"> "Backlight" (逆光)</label>
                </fieldset>
                <fieldset>
                    <legend>
                        <h3>Which track in Campanella is your favorite? [pt.2]</h3>
                    </legend>
                        <label for="ii"><input type="checkbox" class="inline" name="new-options" id="ii" value="ii"> "I'm Invincible"(私は最強)</label>
                        <label for="rm"><input type="checkbox" class="inline" name="new-options" id="rm" value="rm" /> "Readymade" (レディメイド)</label>
                        <label for="ac"><input type="checkbox" class="inline" name="new-options" id="ac" value="ac"> "Ashura-chan" (阿修羅ちゃん)</label>
                        <label for="osman"><input type="checkbox" class="inline" name="new-options" id="osman" value="osman" /> "Osmanthus"(金木犀) feat.Ado</label>
                        <label for="fw"><input type="checkbox" class="inline" name="new-options" id="fw" value="fw"> "Fireworks" (花火)</label>
                </fieldset>
                <fieldset>
                    <legend>
                        <h3>Which track in Campanella is your favorite? [pt.3]</h3>
                    </legend>
                        <label for="ai"><input type="checkbox" class="inline" name="new-options" id="ai" value="ai"> "Aitakute" (会いたくて)</label>
                        <label for="kaga"><input type="checkbox" class="inline" name="new-options" id="kaga" value="kaga"> "Kagakushu" (過学習)</label>
                        <label for="dd"><input type="checkbox" class="inline" name="new-options" id="dd" value="dd" /> "Darling Dance"(ダーリンダンス 歌いました)</label>
                        <label for="freedom"><input type="checkbox" class="inline" name="new-options" id="freedom" value="freedom"> "Freedom"</label>                       
                        <label for="shi"><input type="checkbox" class="inline" name="new-options" id="shi" value="shi" /> "Shikabanese" (シカバネーゼ) feat.Ado</label>
                </fieldset>
                <fieldset>
                    <legend>
                        <h3>Which track in Campanella is your favorite? [pt.4]</h3>
                    </legend>
                        <label for="ena"><input type="checkbox" class="inline" name="new-options" id="ena" value="ena" /> "Eien No Akuruhi"(永遠のあくる日)</label>
                        <label for="gg"><input type="checkbox" class="inline" name="new-options" id="gg" value="gg"> "Gira Gira" (ギラギラ)</label>
                        <label for="mo"><input type="checkbox" class="inline" name="new-options" id="mo" value="mo" /> "Motherland" (マザーランド)</label>
                        <label for="zan"><input type="checkbox" class="inline" name="new-options" id="zan" value="zan" /> "Zanelli" (ザネリ 歌いました)</label>
                        <label for="ktinnf"><input type="checkbox" class="inline" name="new-options" id="ktinnf" value="ktinnf"> "Kokoro to iu Na noFukakai" (心という名の不可解)</label>
                </fieldset>
        </div>
        <div class="container">
            <a href="https://www.cdjapan.co.jp/product/TYCT-69290"><img class="Utattemita"src="https://images.genius.com/e5be218cde05f6f28769607f399a80f8.1000x1000x1.png"alt="Kyougen"></a>
                <fieldset>
                    <legend>
                        <h3>Which track in Utattemita is your favorite?</h3>
                    </legend>
                        <label for="df"><input type="checkbox" class="inline" name="new-options" id="df" value="df"> "Dried Flowers" (ドライフラワー)</label>
                        <label for="kjnnynw"><input type="checkbox" class="inline" name="new-options" id="kjnnynw" value="kjnnynw"> "Kazari jya Nai no yo Namida wa" (飾りじゃないのよ涙は)</label>
                        <label for="aaa"><input type="checkbox" class="inline" name="new-options" id="aaa" value="aaa"> "Aishite Aishite Aishite"(愛して愛して愛して)</label>
                        <label for="cap"><input type="checkbox" class="inline" name="new-options" id="cap" value="cap"> "Crime & Punishment" (罪と罰)</label>
                        <label for="kg"><input type="checkbox" class="inline" name="new-options" id="kg" value="kg"> "Kawaikute Gomen" (可愛くてごめん)</label>
                </fieldset>
                <fieldset>
                    <legend>
                        <h3>Which track in Utattemita is your favorite? [pt.2]</h3>
                    </legend>
                        <label for="vil"><input type="checkbox" class="inline" name="new-options" id="vil" value="vil"> "Villan" (ヴィラン)</label>
                        <label for="gi"><input type="checkbox" class="inline" name="new-options" id="gi" value="gi"> "God-ish" (神っぽいな)</label>
                        <label for="unravel"><input type="checkbox" class="inline" name="new-options" id="unravel" value="unravel"> "Unravel"</label>
                        <label for="bnd"><input type="checkbox" class="inline" name="new-options" id="bnd" value="bnd"> "Buriki no Dance" (ブリキノダンス)</label>
                        <label for="daf"><input type="checkbox" class="inline" name="new-options" id="daf" value="daf"> "Dawn and Fireflies" (夜明けと蛍)</label>
                </fieldset>
        </div>

        <div class="container">
            <footer class="comments">
                <label for="comments">How did you found Ado-san? Share it to us!</label>

                <textarea id="comments" placeholder="I met her..."></textarea>
            </footer>
        </div>
        <div class="container">
            <footer class="comments">
                <label for="comments">Any message for Ado-san? Feel free to share!</label>

                <textarea id="comments" placeholder="Send a message to Ado-san!"></textarea>
                <button type="submit" id="submit" value="submit">Submit</button>
            </footer>
        </div>
    </div>
    </form>
</body>

</html>
