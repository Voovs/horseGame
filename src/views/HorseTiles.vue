<template>
  <div class="main-div">
    <input id="keyinput" style="border-color: white; box-shadow: none;" type="text" v-on:keypress="playRound">
    <div class="board">
      <div class="numbers">
        <div class="num2">2</div>
        <div class="num3">3</div>
        <div class="num4">4</div>
        <div class="num5">5</div>
        <div class="num6">6</div>
        <div class="num7">7</div>
        <div class="num8">8</div>
        <div class="num9">9</div>
        <div class="num10">10</div>
        <div class="num11">11</div>
        <div class="num12">12</div>
      </div>
      <div class="tiles">
        <div id="row2">
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#b89c3f" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80" >
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
        </div>
        <div id="row3">
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#b89c3f" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
        </div>
        <div id="row4">
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#b89c3f" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
        </div>
        <div id="row5">
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#b89c3f" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
        </div>
        <div id="row6">
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#b89c3f" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
        </div>
        <div id="row7">
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#b89c3f" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
        </div>
        <div id="row8">
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#b89c3f" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
        </div>
        <div id="row9">
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#b89c3f" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
        </div>
        <div id="row10">
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#b89c3f" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
        </div>
        <div id="row11">
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#b89c3f" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
        </div>
        <div id="row12">
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#b89c3f" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
          <svg height="80" width="80">
              <circle cx="40" cy="40" r="30" stroke="#333" stroke-width="20" fill="#333" />
            </svg>
        </div>
      </div>
      <div id="diceButton" v-on:click="playRound()" class="diceButton">
        <span>Roll the dice</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Example',
  data: function(){
    return{
      horsePosition: {2: 0, 3: 0, 4: 0, 5: 0, 6: 0, 7: 0, 8: 0, 9: 0, 10: 0, 11: 0, 12: 0},
      lastRoll: 0
    }
  },
  methods: {
    /** Simulates the roll of two standard six sided dice
     * @return {Number} Number 1-12, with bias towards middle numbers
     */
    rollDice() {
      var first = Math.floor(Math.random() * 6) + 1
      var sec = Math.floor(Math.random() * 6) + 1
      return first + sec
    },
    /** Given horsePosition object, will find if any won
     * @param  {object} object Should be this.horsePosition
     * @return {Number}        Will return the number of the winning horse lane
     * @return {Boolean}       Returns false if no horse lane has won
     */
    checkForWin() {
      var object = this.horsePosition
      for (var i = 1; i <= 12; i++) {
        if (i <= 7) {
          if (object[i] === (i+1)) return i
          else continue
        }
        else {
          if (object[i] ===  (8 - (i-7)) ) return i
          else continue
        }
      }
      return false
    },
    updateCurrPosition(roll) {
      var newPosition = this.horsePosition[roll]
      document.getElementById("row" + roll).children[newPosition].children[0].classList.add("currNewPosition") // Adds a currNewPosition class to the current tile
      if (this.lastRoll == roll){
        document.getElementById("row" + roll).children[newPosition - 1].children[0].classList.remove("currNewPosition") // Removes class from previous tile, if it was rolled last turn
      }
      else {
        document.getElementById("row" + roll).children[newPosition - 1].children[0].classList.remove("currPosition")// Removes class from previous tile, if it was not rolled last turn
      }
      document.getElementById("row" + roll).children[newPosition - 1].children[0].classList.add("tileStandard")// Adds standard class to tile
      this.lastRoll = roll
    },
    winProtocol(row) {
      var winPosition = this.horsePosition[row]
      document.getElementById("row" + row).children[winPosition].children[0].classList.remove("currNewPosition")
      document.getElementById("row" + row).children[winPosition].children[0].classList.add("winTile")
      document.getElementById("diceButton").style.display= "none"
      document.getElementById("keyinput").style.display= "none"
    },
    removeLastHighlight() {
      var lastRow = this.lastRoll, lastPosition = this.horsePosition[this.lastRoll]
      if (this.lastRoll === 0) return
      document.getElementById("row" + lastRow).children[lastPosition].children[0].classList.remove("currNewPosition")
      document.getElementById("row" + lastRow).children[lastPosition].children[0].classList.add("currPosition")
    },
    playRound() {
      this.removeLastHighlight()
      var roll = this.rollDice()
      this.horsePosition[roll] += 1
      this.updateCurrPosition(roll)
      if (this.checkForWin() !== false) {
        this.winProtocol(roll)
      }
    }
  },
  computed: {
  },
  props: {
    messageHere:{
      default: "Error 404"
    }
  },
  created() {
  },
  mounted() {
    document.getElementById('keyinput').select()
  },
  destroyed() {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@font-face {
  font-family: PoetsenOne;
  src: url('../assets/PoetsenOne-Regular.ttf')
}
/* General styles */
.main-div{
  margin: 0;
  padding: 0;
  background-color: #DCDCDC
}
.board {
  display: flex;
  justify-content: center;
}

/* Tile styles */
.board .tiles {
  flex-basis: 800px;
}
.board .tiles .currPosition {
  stroke: #b89c3f;
  fill: #333;
}
.board .tiles .currNewPosition {
  stroke: #b89c3f;
  fill: #b83f75;
}
.board .tiles .tileStandard {
  stroke: #333;
  fill: #333;
}
.board .tiles .winTile {
  stroke: #b83f75;
  fill: #b89c3f;
}

/* Writing styles */
.board .numbers {
  color: #333;
  font-size: 80px;
  font-family: PoetsenOne, sans-serif;
  line-height: 1.04;
}
.board .numbers > *::selection {
  background: #333;
  color: #b89c3f;
}
.board .diceButton {
  user-select: none;
  position: absolute;
  top: 70vh;
  left: 67vw;
  width: 450px;
  font-family: PoetsenOne;
  font-size: 100px;
  color: #b83f75;
  background-color: #333;
  border-radius: 100px;
  border: 30px solid #333;
  transition-property: top, background-color, border, color;
  transition-duration: .7s;
  transition-timing-function: ease;
  transition-delay: none;
}
.board .diceButton:hover {
  cursor: pointer;
  top: 68vh;
  left: 67vw;
  color: #b89c3f;
  background-color: #3c3c3c;
  border-radius: 100px;
  border: 30px solid #3c3c3c;
}
.board .diceButton span {
  text-align: left;
  padding: 0 20px;
}
</style>
