Create baseball scoreboard

State

How to name our state object?

var scoreBoard={};

//properties and methods
scoreBoard.fieldName = "Heinz" //string
scoreBoard.inningsCompleted = []; // ??
scoreBoard.count = {};
scoreBoard.

START

INIT creating state obj-scoreBoard
check for existing data
    if we have data, populate the scoreBoard-show current state based on stored data
//assume we are the operator
establish click handlers for control buttons
business logic, logic (determines what we are going to have happen-3 outs updates scoreboard)
scoreBoard.init();

Class ScoreBoard(){
    //constructor

    //properties
    let strikes = 0; //set to default value of 0
    strikes = [];
}
    //Methods

    init(data){
        //when object is created

    }

    onStateChange(){
        // ??
        //check for three strikes
        //check for 4 balls

        if(strikes.length>2){
            addOut();
            resetBallsStrikes();
        }
        //check 
    }

