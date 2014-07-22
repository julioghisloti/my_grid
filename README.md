#MyGrid
## My personal compass grid

### Some code example

This is a very simple grid system. But works pretty well.
For use this, you only need know this things:

- All element attribute: margin, position, padding... has a "_" (one underscore) like a prefix

		//Column
		._col
	
		//Align element left
		._left
	
		//Align element left
		._right
	
		//Align element center
		._center


- Element width size has two underscore "__"

		//Sizes
		.__100pc{
			margin: 0.5%;
			width: 97%;
			max-width: 1700px;
		}

		.__90pc{
			margin: 0.5%;
			width: 87%;
			max-width: 1500px;
		}

		.__80pc{
			margin: 0.5%;
			width: 77%;
			max-width: 1200px;
		}

		.__70pc{
			margin: 0.5%;
			width: 67%;
		}

		.__60pc{
			margin: 0.5%;
			width: 57%;
		}

		.__50pc{
			margin: 0.5%;
			width: 47%;
		}

		.__40pc{
			margin: 0.5%;
			width: 37%;
		}

		.__30pc{
			margin: 0.5%;
			width: 27%;
		}

		.__20pc{
			margin: 0.5%;
			width: 17%;
		}
		
- Basic margin and padding options

		//-- nomargin	
		._nm{margin: 0% !important;}

		//-- no margin top
		._n-mt{margin-top: 0% !important;}

		//-- no margin right
		._n-mr{margin-right: 0% !important;}

		//-- no margin bottom
		._n-mb{margin-bottom: 0% !important;}

		//-- no margin left
		._n-ml{margin-left: 0% !important;}
		
		
		
		//-- no padding	
		._np{padding: 0% !important;}

		//-- no padding top
		._n-pt{padding-top: 0% !important;}

		//-- no padding right
		._n-pr{padding-right: 0% !important;}

		//-- no padding bottom
		._n-pb{padding-bottom: 0% !important;}

		//-- no padding left
		._n-pl{padding-left: 0% !important;}
		
		

Until this moment we only have this options. But you can help me. You can create a new options, sizes and utilities. Go ahead!

 *sorry for my amateur english :(*