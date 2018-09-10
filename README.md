
# An Exploratory Repository of ShuxianFan

## About The Repository

This is an exploratory repository of ShuxianFan [@ShuxianFan](https://github.com/ShuxianFan) for the course STAT545A in UBC as an exercise to elaborate and test out different features of Markdown Text. 

Here you will find:
  
  :memo: A [**README**](https://github.com/STAT545-UBC-students/hw01-ShuxianFan/blob/master/README.md) file that contains the basic information of the repository and some [**fun facts**](#fun-facts-about-myself) about me!
  
  :bar_chart: An [**R_Markdown**](https://github.com/STAT545-UBC-students/hw01-ShuxianFan/blob/master/hw01_aids.Rmd) document that presents some interesting exploratory data analysis on the `aids` dataset. The GitHub Markdown output can be found [**here**](https://github.com/STAT545-UBC-students/hw01-ShuxianFan/blob/master/hw01_aids.md).


## Fun Facts about Myself
### :smile_cat: Name 
I love my hard-to-pronounce name: Shuxian Fan. (give it a try - shoe she-Ann fan) 
My parents gave me this name with their best wishes as the Chinese Characters *Shu* and *Xian* means 
> “good, pure, virtuous, charming”. 

I also go by Trinity and yes it comes from the movie [*The Matrix*](https://en.wikipedia.org/wiki/The_Matrix). :joy: 

### :smirk_cat: Major
I studied in Financial Mathematics before I decided to transfer to UBC to change my major three years ago. Statistics was my second choice but it turns out to be the passion I found.

### :heart_eyes_cat: Things I Enjoy

#### :movie_camera: **Movies**
![partial_list](/hw01_README_files/movie.JPG)

#### :airplane: **Trips**
- [x] London
- [x] Toronto
- [x] Kyoto
- [ ] Istanbul

Destination  | To-do
------------ | -------------
London | The Sherlock Holmes Museum
Toronto | Niagara Falls
Kyoto | Fireworks

#### :video_game: Games
![game](/hw01_README_files/game.JPG)

### :sparkles: Research Interest
Currently I am working on a project that involves statistical analysis of spatial point process. 

  - \*Always willing to try out more things!\*

## Final Remarks
An interesting anecdote about Fast inverse square root as an end:
> The following code is the fast inverse square root implementation from Quake III Arena, stripped of C preprocessor directives, but including the exact original comment text:

```C
float Q_rsqrt( float number )
{
	long i;
	float x2, y;
	const float threehalfs = 1.5F;

	x2 = number * 0.5F;
	y  = number;
	i  = * ( long * ) &y;                       // evil floating point bit level hacking
	i  = 0x5f3759df - ( i >> 1 );               // what the fuck? 
	y  = * ( float * ) &i;
	y  = y * ( threehalfs - ( x2 * y * y ) );   // 1st iteration
//	y  = y * ( threehalfs - ( x2 * y * y ) );   // 2nd iteration, this can be removed

	return y;
}
```

Read about more [here](https://en.wikipedia.org/wiki/Fast_inverse_square_root).



