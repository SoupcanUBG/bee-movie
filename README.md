# bee-movie                           
                 
git clone https://github.com/SoupcanUBG/bee-movie.git               
                        
ffmpeg -i ~/bee-movie/mp4.mp4 -filter:v "setpts=12.67*PTS" -an ~/movie.mp4              

