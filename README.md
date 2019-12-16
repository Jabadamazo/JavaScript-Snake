

Other than the full screen mode demonstrated in the code, it can also be 
initialized in div tags within a page. Example:

    var mySnakeBoard = new SNAKE.Board( {
                                            boardContainer: "game-area",
                                            fullScreen: false,
                                            width: 1000,
                                            height:1000
                                        });
                                    
The comments are formatted a little strange because at the time I was playing
around with YUI Doc.
