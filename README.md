# baseBallScoreBoard

//main.js

//START

//INIT
//create state object

scoreBoard.data = "";

function init(){
    console.log("hello world!");
}

Class ScoreBoard {

//showing default values for what view has to show
    constructor(){
        this.fieldName = "Wrigley Field";
        this.data = [];   //sent to us via API
        this.balls = 0;
        this.strikes = 0;
        this.outs = 0;
        this.innings = [];  //innings = [0,1,2,0]; for example
        this.runs = 0;
    }

    addBall(){
        //increase ball count by one
        this.balls++;
    }

    addStrike(){
        this.strikes++;
    }

    addOut(){
        this.outs++;
    }

    addInning(){
        this.innings.push(score);
    }

    addRuns(){
        this.runs++;
    }


}

let scoreBoard = new ScoreBoard();