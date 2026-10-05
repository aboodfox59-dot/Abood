<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>طِفلتي 🐥❤️</title>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Tahoma, Arial, sans-serif;
    min-height: 100vh;
    background: linear-gradient(135deg, #ffd6e7, #ffeef5, #ffdce9);
    color: #542638;
    overflow-x: hidden;
}

.hearts {
    position: fixed;
    inset: 0;
    pointer-events: none;
    overflow: hidden;
    z-index: 0;
}

.heart {
    position: absolute;
    bottom: -30px;
    font-size: 20px;
    animation: floatUp linear infinite;
    opacity: 0.55;
}

.heart:nth-child(1) { left: 10%; animation-duration: 8s; }
.heart:nth-child(2) { left: 25%; animation-duration: 11s; animation-delay: 2s; }
.heart:nth-child(3) { left: 45%; animation-duration: 9s; animation-delay: 1s; }
.heart:nth-child(4) { left: 65%; animation-duration: 12s; animation-delay: 3s; }
.heart:nth-child(5) { left: 82%; animation-duration: 10s; animation-delay: 1.5s; }

@keyframes floatUp {
    0% {
        transform: translateY(0) scale(0.8) rotate(0deg);
        opacity: 0;
    }
    20% {
        opacity: 0.6;
    }
    100% {
        transform: translateY(-110vh) scale(1.3) rotate(25deg);
        opacity: 0;
    }
}

.container {
    position: relative;
    z-index: 1;
    max-width: 600px;
    margin: auto;
    padding: 35px 18px 50px;
}

.hero {
    text-align: center;
    padding: 30px 10px 25px;
}

.chick {
    font-size: 65px;
    animation: bounce 2s infinite;
}

@keyframes bounce {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-8px); }
}

h1 {
    font-size: 34px;
    margin: 12px 0 8px;
    color: #8e3154;
}

.subtitle {
    font-size: 16px;
    line-height: 1.8;
    color: #795264;
}

.intro {
    background: rgba(255,255,255,0.65);
    border: 1px solid rgba(255,255,255,0.8);
    border-radius: 25px;
    padding: 22px;
    text-align: center;
    margin-bottom: 25px;
    box-shadow: 0 10px 30px rgba(120,40,70,0.08);
}

.intro p {
    line-height: 1.9;
}

.buttons {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
}

button {
    border: none;
    padding: 17px 12px;
    border-radius: 18px;
    background: rgba(255,255,255,0.8);
    color: #653044;
    font-size: 15px;
    font-weight: 600;
    cursor: pointer;
    box-shadow: 0 7px 20px rgba(100,30,60,0.08);
    transition: 0.2s;
}

button:hover {
    transform: translateY(-3px);
    background: white;
}

button:active {
    transform: scale(0.97);
}

.secret {
    grid-column: 1 / -1;
    background: linear-gradient(135deg, #8e3154, #b84e76);
    color: white;
}

.footer {
    text-align: center;
    margin-top: 35px;
    font-size: 14px;
    opacity: 0.7;
}

/* نافذة الرسالة */

.modal {
    display: none;
    position: fixed;
    inset: 0;
    background: rgba(50,15,30,0.55);
    backdrop-filter: blur(7px);
    z-index: 10;
    align-items: center;
    justify-content: center;
    padding: 20px;
}

.modal.show {
    display: flex;
}

.message-box {
    width: 100%;
    max-width: 470px;
    background: #fff8fb;
    border-radius: 28px;
    padding: 30px 24px;
    text-align: center;
    box-shadow: 0 20px 60px rgba(0,0,0,0.2);
    animation: pop 0.3s ease;
}

@keyframes pop {
    from {
        transform: scale(0.8);
        opacity: 0;
    }
    to {
        transform: scale(1);
        opacity: 1;
    }
}

.message-icon {
    font-size: 45px;
    margin-bottom: 12px;
}

.message-title {
    color: #8e3154;
    font-size: 23px;
    margin-bottom: 15px;
}

.message-text {
    font-size: 17px;
    line-height: 2;
    color: #5e3b49;
}

.close {
    margin-top: 22px;
    background: #8e3154;
    color: white;
    width: 100%;
}

/* شاشة البداية */

.welcome {
    position: fixed;
    inset: 0;
    z-index: 20;
    background: linear-gradient(135deg, #ffd6e7, #fff0f6);
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 25px;
    text-align: center;
}

.welcome.hidden {
    display: none;
}

.welcome-box {
    max-width: 450px;
}

.welcome-box .big {
    font-size: 80px;
    margin-bottom: 10px;
}

.welcome-box h2 {
    font-size: 32px;
    color: #8e3154;
    margin-bottom: 12px;
}

.welcome-box p {
    line-height: 1.9;
    color: #795264;
    margin-bottom: 25px;
}

.start {
    background: linear-gradient(135deg, #8e3154, #c6537b);
    color: white;
    padding: 17px 35px;
    border-radius: 50px;
    font-size: 17px;
}

@media (max-width: 430px) {
    h1 {
        font-size: 29px;
    }

    .buttons {
        grid-template-columns: 1fr;
    }

    .secret {
        grid-column: auto;
    }
}
</style>
</head>

<body>

<!-- شاشة البداية -->

<div class="welcome" id="welcome">
    <div class="welcome-box">
        <div class="big">🐥❤️</div>

        <h2>لَـ طِفلتي</h2>

        <p>
            عملتلك مكان صغير...
            فيه اكم كلمة مني إلك،
            عشان تلاقيها وقت ما تحتاجيها بأي وقت 🫂.
        </p>

        <button class="start" onclick="startSite()">
            افتحي رسائلك 💌
        </button>
    </div>
</div>


<!-- القلوب -->

<div class="hearts">
    <div class="heart">❤️</div>
    <div class="heart">🤍</div>
    <div class="heart">💕</div>
    <div class="heart">❤️</div>
    <div class="heart">💗</div>
</div>


<!-- الموقع -->

<div class="container">

    <div class="hero">
        <div class="chick">🐥</div>

        <h1>رسائل لَـ طِفلتي ❤️</h1>

        <p class="subtitle">
            كل رسالة إلها وقتها...
            افتحي الّي يشبه شعورك يروحي 🌚❤️.
        </p>
    </div>


    <div class="intro">
        <p>
            يمكن المسافة بيننا تمنعني اكون جنبك بكل لحظة،
            بس ما بتمنعني اكون معك من بعيد و موجود بقلبك ❤️.
        </p>
    </div>


    <div class="buttons">

        <button onclick="openMessage('miss')">
            💌 لما تشتاقيلي
        </button>

        <button onclick="openMessage('sad')">
           🥹 لما تكوني زعلانة
        </button>

        <button onclick="openMessage('doubt')">
            ❤️ لما تشكي بحبي
        </button>

        <button onclick="openMessage('sleep')">
           🌚 قبل ما تنامي
        </button>

        <button onclick="openMessage('bad')">
           ❤️ لما يكون يومك مش احسن اشي
        </button>

        <button onclick="openMessage('happy')">
           🙈 لما تكوني مبسوطة
        </button>

        <button onclick="openMessage('hug')">
            🫂 لما تحتاجي حضن
        </button>

        <button class="secret" onclick="openMessage('secret')">
            🔒 رسالة سرية
        </button>

    </div>


    <div class="footer">
        عملته إلك وبس يَـبطة 🐥❤️.
    </div>

</div>


<!-- نافذة الرسالة -->

<div class="modal" id="modal">

    <div class="message-box">

        <div class="message-icon" id="messageIcon"></div>

        <h2 class="message-title" id="messageTitle"></h2>

        <p class="message-text" id="messageText"></p>

        <button class="close" onclick="closeMessage()">
            رجعيلي 💗
        </button>

    </div>

</div>


<script>

const messages = {

    miss: {
        icon: "💌",
        title: "لما تشتاقيلي",
        text: `
        إذا اشتقتيلي، تذكري دايماً إنه في شخص هون
        ممكن يكون مشتاقلك أكثر مما تتخيلي،
        يمكن المسافة بيننا تمنعني أكون جنبك،
        بس ما بتقدر تمنعني أكون معك يقلبي، الله بعلم كم مرة باليوم بحسّ بشعور الإشتياق الك، حتى باللحظة الّي نكون نحكي انا وياكِ فيها بكون بشتاقلك 🥹❤️، بشتاقلك دايماً كل دقيقة كل ثانية كل ساعة كل يوم يعيوني والله🥹🥹🥹🥹❤️.
        `
    },

    sad: {
        icon: "🥹",
        title: "إذا كنتِ زعلانة",
        text: `
        
        رغم زعلك من الدنيا كلها آخر فترة،
        بدي دايماً تتذكري إنك مش لحالك.
        أنا هون معك بشاركك بزعلك وحزنك وفرحك، وبهمني أشوفك بخير دايماً ❤️🫂، بدعي ربنا يبعد عنك الزعل يحبيبتي وما يبعثلك الّا السعادة وهداة بال، طول مَ انا معك عمري ما  حسمح اشوف بعيونك الزعل، لإنه عيونك هذول ما بستاهلوا يزعلوا، بستاهلوا دايماً يكونو مبسوطين ويدمعوا فرح مش حزن ❤️.
        `
    },

    doubt: {
        icon: "❤️",
        title: "إذا شكّيتي بحبي",
        text: `
        إذا شكّيتي بحبي بيوم،
        ارجعي لهالرسالة.
        أنا ما اخترتك عشان يوم حلو أو لحظة حلوة،
        اخترتك لأنه وجودك صار يعنيلي كثير.
        وبحبك بطريقة ما بتحتاج كل يوم إثبات جديد، اناا ما نقّيتك من بين الكل عبث، ولا اجيت عشان فترة مؤقتة، انتِ بالنسبة الي مثل العطر، شمّيته وعجبني وقطعت كل انواع العطور الثانية وتعلقت بهالعطر المعيّن هاض! انا يروحي الهدف الرئيسي لوجودي معك هو انّي اصونك مش اخلّيكِ تشكّي فيا، ويعلم ربنا انّي من وراكي لسا كيف من قدامك؟ واحسن على اضعاف، لو فيا نيّة سوء تجاهك كان ما تلاقيني بهاي الفرحة معك وكان ما تلاقيني معك وانا متطمن انّك هتكملي معي، كان ما بصيبني شعور حلو كل مرة بحكي معك فيها، انتِ بنتي وطِفلتي وامانة برقبتي انا مش برقبة حدا ثاني، والأمانة عمرها ما تنخان يعيوني 🥹❤️❤️، انتِ الي وانكتبتي تكوني الي، مش هفكّر افرّط فيكي مهما حصل.
        `
    },

    sleep: {
        icon: "🌚",
        title: "قبل مَ تنامي",
        text: `
        بتمنى مع الظروف الي احنا فيها يهدى كلشي براسك يحبيبتي ويهوّن عليكي كلشي ويهدّي بالك 😔❤️،
        نامي وأنتِ عارفة إنك اغلى حدا عقلبي،
        وإنه في شخص يتمنالك راحة
        وقلب مطمئن دايماً ❤️🫂،
        تصبحيييييييييييييييييييييييييييي ع الففففففف مليووووووون خيييييييييييييييييييييرررررررررر  يَ طِفلتي. 🌙❤️
        `
    },

    bad: {
        icon: "❤️",
        title: "لما يكون يومك مش احسن اشي",
        text: `
        اليوم السيئ مش يعني إنه حياتك سيئة،
        بكرا فرصة جديدة يروحي، ومع وجودي معك وبحدّك هخلّي كل ايامك فرح وسعادة ومش هخلّي يومك يكون سيئ وعد 👆🏼❤️.
        لا تلومي نفسك ع كلشي،
        وخلي اليوم يعدّي.
        وإذا احتجتي حدا يسمعك، أنا موجود الك وعشانك 🫂.
        `
    },

    happy: {
        icon: "🙈",
        title: "لما تكوني مبسوطة",
        text: `
        إذا كنتِ مبسوطة،
        فأنا مبسوط لأنك مبسوطة.
        احتفظي بهاللحظة دايماً،
        اضحكي كثير،
        وخلي فرحتك تكبر اكثر واكثر، لإنه مافي اشي بهالدنيا مستاهل نزعل عشانو، الناس؟ تروح وتيجي وطز بأحسن واحد، انا لما اشوفك مبسوطة بحس كل اشي كنت بدوّر عليه وكثير تعبت وانا بدوّر عليه وما لقيته، لما اشوفك مبسوطة زي كإني لقيت الإشي هاض الّي كنت بدوّر عليه من زمان عشان الاقي راحتي فيه وفرحتي 🥹❤️، بدي دايماً تكوني مبسوطة وما تسمحي لأي اشي يأثّر عليكِ او يزعلك لإنه انتِ تستاهلي بس تكوني مبسوطة والزعل ما يلبق لعيونك الّي شايف فيهم احلى مستقبل بني آدم ممكن اشوفه بالكون 🥹🥹🥹🥹🥹❤️❤️❤️❤️.
        `
    },

    hug: {
        icon: "🫂",
        title: "تعاليييييييي ...",
        text: `
        اعتبري هاي الرسالة حضن طويل بدون كلام.
        خليكيييي هون، واتخيّلي انّي قاعد بحضنك 🥹❤️🫂🫂🫂🫂🫂🫂🫂🫂🫂🫂.
        بكل مرة بدك حضن تعالي هون وانا هكون دايماً هون وبحضنك عادي لو مجرّد تخيّل بس المهم الإحساس موجود 🥹❤️.
        `
    },

    secret: {
        icon: "🔒",
        title: "رسالة سرية",
        text: `
        بين كل الأشياء الّي ممكن اكتبها،
        في اشي واحد ما بحتاج أكتبه كثير...
        أنا بحب وجودك بحياتي ❤️، ما بعرف اذا الإشي هاض بتلاحظيه عليّ، بس لو اجيتيني قبل وشفتي كيف كانت حياتي وكيف كنت انا بالضبط، هتعرفي انّك انتِ غيّرتيلي حياتي، وبنيتِ جواي رُوح جديدة للحياة، خلّيتيني الي نفس اعيش، كنت جسد بلا رُوح من قبلك، ومعك صرت انسان ثاني عبود الجديد الي نفسو منفتحة عكلشي الّي ربنا موفقو بسبب وجودك بحياته، الّي الناس رجعت تحبه بعد ما كان قاطع علاقتو بالكل، من اصحاب من قرايب من معارف … بحبك يا احلى اشي صار بحياتي يا الّي لو اضل احكي من هون لبكرا ما بخلّص وبوفيلك حقك 😔. 
        بتمنى دايماً اكون سبب صغير من اسباب فرحتك زي ما انتِ دايماً سبب بفرحتي ❤️.
هعمل المستحيل عشانك ومش عشان صارت مشكلة من ناس حقودة وتافهة، اروح واغيّر قراري! انا كلمتي كلمة وقراري قرار، انا مُستتب عليكي لو مهما صار لو الشغلة عليها اهل مُستعد اخسر الدنيا كلها لأجلك وولا مخلوق فارق عندي وشو مبدو يصير يصير، كل واحد فينا بدوّر على راحته وانا راحتي لقيتها معك.
وانا وعدتك وبرجع اوعدك ، وعد غير اخلّي الكل يحكي بقصة حُبنا واخلّي الكل يغار منك ❤️.
        `
    }

};


function startSite() {
    document.getElementById("welcome").classList.add("hidden");
}


function openMessage(type) {

    const message = messages[type];

    document.getElementById("messageIcon").textContent = message.icon;

    document.getElementById("messageTitle").textContent = message.title;

    document.getElementById("messageText").innerHTML =
        message.text.replace(/\n/g, "<br>");

    document.getElementById("modal").classList.add("show");
}


function closeMessage() {
    document.getElementById("modal").classList.remove("show");
}


// إغلاق النافذة عند الضغط خارج الرسالة

document.getElementById("modal").addEventListener("click", function(e) {

    if (e.target === this) {
        closeMessage();
    }

});

</script>

</body>
</html>
