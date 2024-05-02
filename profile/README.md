<div align="center">
    <h1>Neural Net Poker</h1>
    <h4>Senior Design Group</h4>
</div>

###


###

<h3 align="left">About Us</h3>

###

<p align="left">
We are a Senior Design group for COSC401/402 at the University of Tennessee, Knoxville. Our project is to create a neural network based poker bot that can be played against.
</p>

###

<h3 align="left">🛠 The Team</h3>

###

<div align="left">
    <div>
        <a href="https://github.com/JMcknight75" target="_blank">
            Justin McKnight:
        </a>
        Back-end & Team Lead
    </div>
    <div>
        <a href="https://github.com/Jxk0be" target="_blank">
            Jake Shoffner:
        </a>
        Front-end
    </div>
    <div>
        <a href="https://github.com/Brandon-Marth" target="_blank">
            Brandon Marth:
        </a>
        Front-end
    </div>
    <div>
        <a href="https://github.com/jdixon34-cs340" target="_blank">
            Jared Dixon:
        </a>
        Back-end
    </div>
    <div>
        <a href="https://github.com/ColinC5" target="_blank">
            Colin Canonaco:
        </a>
        Back-end
    </div>
</div>

###

<h3 align="left">Project Summary</h3>

###

<p align="left">
The purpose of using deep reinforcement learning on an imperfect information game like poker, is to show the potential application of reinforcement learning in areas with incomplete information and unpredictable human elements.

Researching the implementation of deep reinforcement learning with imperfect information games can advance the field of artificial intelligence in playing games with limited information. Our goal was to create a bot that can competitively play the game of poker against a human opponent. In heads up limited holdem poker, we expect the bot to beat amateur level players more than half the time over a sufficient amount of games. An accessible website is provided for users to easily play against the bot.

Design concepts our team considered were: the training algorithm, training software, demonstration methods for the bot, and choosing between heads up limited poker vs no-limit poker. For the training algorithm, we decided between evolutionary reinforcement learning, deep Q-learning, and neural fictitious self-play (NFSP). We eventually decided on a combination of NFSP and deep Q-learning because they were well suited to the game and would provide the best results. We considered using TensorFlow or PyTorch, and we ultimately decided to use PyTorch as the RLCard poker environment we were going to use used PyTorch. When deciding how to showcase the bot, we deliberated between hosting the bot on our website, or using it through an API. We decided to host it on Google Cloud due to concerns about the viability of running it locally. When determining which variant of poker the neural network will play, we chose heads up limit holdem poker due to its smaller action space compared to no-limit.
</p>
