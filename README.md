import React from 'react';
import './App.css';
import {AiOutlineTwitter,AiTwotoneStar,AiOutlineSearch,AiOutlinePicture,AiOutlineAlignLeft,AiOutlineSmile,AiOutlineFileGif,AiOutlineDown} from 'react-icons/ai'
import {BiHomeCircle,BiHash,BiBell} from 'react-icons/bi'
import {MdMailOutline,MdBookmarkBorder} from 'react-icons/md'
import {FaUserCircle,FaEllipsisH,FaRegComment,FaRetweet,FaRegHeart} from 'react-icons/fa'
import{BsCardText,BsUpload,BsGear} from 'react-icons/bs'
function App() {
  return (
    <div className="App">
      <div className="Main">

        <div className="Sidebar_Area">
          <div className="Twitter">
          <AiOutlineTwitter color="#008080" fontSize="2.3rem"/>
          </div>
          
        <div className="Icons">
         <BiHomeCircle color="#1DA1F2" fontSize="2rem"/>
            <div>Home</div>
        </div>
  
        
        <div className="Icons">
         <BiHash color="#1DA1F2" fontSize="2rem"/>
            <div>Explore</div>
        </div>

        <div className="Icons">
         <BiBell color="#1DA1F2" fontSize="2rem"/>
            <div>Notifications</div>
        </div>

        <div className="Icons">
         <MdMailOutline color="#1DA1F2" fontSize="2rem"/>
            <div>Messagas</div>
            </div>

            <div className="Icons">
         <MdBookmarkBorder  color="#1DA1F2" fontSize="2rem"/>
            <div>BookMarks</div>
        </div>

        <div className="Icons">
         <BsCardText  color="#1DA1F2" fontSize="2rem"/>
            <div>Lists</div>
        </div>

        <div className="Icons">
         <FaUserCircle  color="#1DA1F2" fontSize="2rem"/>
            <div>Profiles</div>
            </div>

        <div className="Icons">
         <FaEllipsisH  color="#1DA1F2" fontSize="2rem"/>
            <div>More</div>
            </div>

            <div className="Icons">
         <button className="btn">
           Tweet
           </button>
      </div>
</div>

      <div className="Main_Area">
          <div className="Home">
            <div className="home">
              Home
            </div>
            <div className="Star_icon">
              <AiTwotoneStar color="#1DA1F2" fontSize="2rem"/>
            </div>
          </div>
          <br></br>
          <div className="Creat_post">
            <div className="Add_text">
              <div className="Profile">
                <img src="/images/profile1.jpg" alt="dp" style={{height:"35px",width:"35px",borderRadius:"50%"}}/>
              </div>
              <input type="post"placeholder="What's Happening"/>
            

          <div className="Btns">
             <div className="Icons">
                <div className="Btns_icon">
            <AiOutlinePicture fontSize="1.5rem" color="1DA1F2"/>
          </div>

          <div className="Btns_icon">
            <AiOutlineFileGif  fontSize="1.5rem" color="1DA1F2"/>
          </div>
          
           <div className="Btns_icon">
            <AiOutlineAlignLeft fontSize="1.5rem" color="1DA1F2"/>
          </div>
        
           <div className="Btns_icon">
            <AiOutlineSmile fontSize="1.5rem" color="1DA1F2"/>
          </div>
          <div className="Tweets">
            <button className="btns-tweet">
              Tweet
            </button>
          </div>
          </div>
          </div>
          </div>
          </div>
          

          <div className="posted_Area">
            <div className="Profile">
              <div className="User_Detail">
                <img src="/images/profile1.jpg" alt="logo"style={{height:"30px",width:"30px",borderRadius:"50%"}}/>
                <div className="User_Name">Girish chinival</div>
                <div className="User_id">@Girish_chinival</div>
                </div>

                <div className="Drop_down">
                  <AiOutlineDown fontSize="1rem"/>

                </div>
                </div>
                <div className="Quotes">
                  World is beauty when you know the thigs properly
                </div>
                <br></br>
                <div className="Profile_images">
                  <img src="/images/profile3.jpg" alt="profile"style={{width:"100%",height:"23rem",objectfit:"fill"}}/>
                </div>
               
                <div className="Comment_Section">
                  <div className="comment">
                    <FaRegComment fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRetweet fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRegHeart fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <BsUpload fontSize="1.4rem"/>
                  </div>
                </div>
              </div>
              <br></br>
              <div className="posted_Area">
            <div className="Profile">
              <div className="User_Detail">
                <img src="/images/profile1.jpg" alt="logo"style={{height:"30px",width:"30px",borderRadius:"50%"}}/>
                <div className="User_Name">Girish chinival</div>
                <div className="User_id">@Girish_chinival</div>
                </div>

                <div className="Drop_down">
                  <AiOutlineDown fontSize="1rem"/>

                </div>
                </div>
                <div className="Quotes">
                  World is beauty when you know the thigs properly
                </div>
                <br></br>
                <div className="Profile_images">
                  <img src="/images/profile5.jpg" alt="profile"style={{width:"100%",height:"23rem",objectfit:"fill"}}/>
                </div>
               
                <div className="Comment_Section">
                  <div className="comment">
                    <FaRegComment fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRetweet fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRegHeart fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <BsUpload fontSize="1.4rem"/>
                  </div>
                </div>
              </div>
              <br></br>
              <div className="posted_Area">
            <div className="Profile">
              <div className="User_Detail">
                <img src="/images/profile1.jpg" alt="logo"style={{height:"30px",width:"30px",borderRadius:"50%"}}/>
                <div className="User_Name">Girish chinival</div>
                <div className="User_id">@Girish_chinival</div>
                </div>

                <div className="Drop_down">
                  <AiOutlineDown fontSize="1rem"/>

                </div>
                </div>
                <div className="Quotes">
                  World is beauty when you know the thigs properly
                </div>
                <br></br>
                <div className="Profile_images">
                  <img src="/images/fl.jpg" alt="profile"style={{width:"100%",height:"23rem",objectfit:"fill"}}/>
                </div>
               
                <div className="Comment_Section">
                  <div className="comment">
                    <FaRegComment fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRetweet fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRegHeart fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <BsUpload fontSize="1.4rem"/>
                  </div>
                </div>
              </div>
              <br></br>
              <div className="posted_Area">
            <div className="Profile">
              <div className="User_Detail">
                <img src="/images/profile1.jpg" alt="logo"style={{height:"30px",width:"30px",borderRadius:"50%"}}/>
                <div className="User_Name">Girish chinival</div>
                <div className="User_id">@Girish_chinival</div>
                </div>

                <div className="Drop_down">
                  <AiOutlineDown fontSize="1rem"/>

                </div>
                </div>
                <div className="Quotes">
                  World is beauty when you know the thigs properly
                </div>
                <br></br>
                <div className="Profile_images">
                  <img src="/images/profile1.jpg" alt="profile"style={{width:"100%",height:"23rem",objectfit:"fill"}}/>
                </div>
               
                <div className="Comment_Section">
                  <div className="comment">
                    <FaRegComment fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRetweet fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRegHeart fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <BsUpload fontSize="1.4rem"/>
                  </div>
                </div>
              </div>
              <br></br>
              <div className="posted_Area">
            <div className="Profile">
              <div className="User_Detail">
                <img src="/images/profile1.jpg" alt="logo"style={{height:"30px",width:"30px",borderRadius:"50%"}}/>
                <div className="User_Name">Girish chinival</div>
                <div className="User_id">@Girish_chinival</div>
                </div>

                <div className="Drop_down">
                  <AiOutlineDown fontSize="1rem"/>

                </div>
                </div>
                <div className="Quotes">
                  World is beauty when you know the thigs properly
                </div>
                <br></br>
                <div className="Profile_images">
                  <img src="/images/profile2.jpg" alt="profile"style={{width:"100%",height:"23rem",objectfit:"fill"}}/>
                </div>
               
                <div className="Comment_Section">
                  <div className="comment">
                    <FaRegComment fontSize="1.4rem"/>
![logo](https://user-images.githubusercontent.com/105573156/171133181-ff5bb36c-80d1-444d-8d4f-aa685c8c1035.svg)
                  </div>

                  <div className="comment">
                    <FaRetweet fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRegHeart fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <BsUpload fontSize="1.4rem"/>
                  </div>
                </div>
              </div>
              <br></br>
              <div className="posted_Area">
            <div className="Profile">
              <div className="User_Detail">
                <img src="/images/profile1.jpg" alt="logo"style={{height:"30px",width:"30px",borderRadius:"50%"}}/>
                <div className="User_Name">Girish chinival</div>
                <div className="User_id">@Girish_chinival</div>
                </div>

                <div className="Drop_down">
                  <AiOutlineDown fontSize="1rem"/>

                </div>
                </div>
                <div className="Quotes">
                  World is beauty when you know the thigs properly
                </div>
                <br></br>
                <div className="Profile_images">
                  <img src="/images/flight2.jpg" alt="profile"style={{width:"100%",height:"23rem",objectfit:"fill"}}/>
                </div>
               
                <div className="Comment_Section">
                  <div className="comment">
                    <FaRegComment fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRetweet fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRegHeart fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <BsUpload fontSize="1.4rem"/>
                  </div>
                </div>
              </div>
              <br></br>
              <div className="posted_Area">
            <div className="Profile">
              <div className="User_Detail">
                <img src="/images/profile1.jpg" alt="logo"style={{height:"30px",width:"30px",borderRadius:"50%"}}/>
                <div className="User_Name">Girish chinival</div>
                <div className="User_id">@Girish_chinival</div>
                </div>

                <div className="Drop_down">
                  <AiOutlineDown fontSize="1rem"/>

                </div>
                </div>
                <div className="Quotes">
                  World is beauty when you know the thigs properly
                </div>
                <br></br>
                <div className="Profile_images">
                  <img src="/images/profile2.jpg" alt="profile"style={{width:"100%",height:"23rem",objectfit:"fill"}}/>
                </div>
               
                <div className="Comment_Section">
                  <div className="comment">
                    <FaRegComment fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRetweet fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRegHeart fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <BsUpload fontSize="1.4rem"/>
                  </div>
                </div>
              </div>
              <br></br>
              <div className="posted_Area">
            <div className="Profile">
              <div className="User_Detail">
                <img src="/images/profile1.jpg" alt="logo"style={{height:"30px",width:"30px",borderRadius:"50%"}}/>
                <div className="User_Name">Girish chinival</div>
                <div className="User_id">@Girish_chinival</div>
                </div>

                <div className="Drop_down">
                  <AiOutlineDown fontSize="1rem"/>

                </div>
                </div>
                <div className="Quotes">
                  World is beauty when you know the thigs properly
                </div>
                <br></br>
                <div className="Profile_images">
                  <img src="/images/raja king.jpeg" alt="profile"style={{width:"100%",height:"23rem",objectfit:"fill"}}/>
                </div>
               
                <div className="Comment_Section">
                  <div className="comment">
                    <FaRegComment fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRetweet fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRegHeart fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <BsUpload fontSize="1.4rem"/>
                  </div>
                </div>
              </div>
              <br></br>
              <div className="posted_Area">
            <div className="Profile">
              <div className="User_Detail">
                <img src="/images/profile1.jpg" alt="logo"style={{height:"30px",width:"30px",borderRadius:"50%"}}/>
                <div className="User_Name">Girish chinival</div>
                <div className="User_id">@Girish_chinival</div>
                </div>

                <div className="Drop_down">
                  <AiOutlineDown fontSize="1rem"/>

                </div>
                </div>
                <div className="Quotes">
                  World is beauty when you know the thigs properly
                </div>
                <br></br>
                <div className="Profile_images">
                  <img src="/images/flight2.jpg" alt="profile"style={{width:"100%",height:"23rem",objectfit:"fill"}}/>
                </div>
               
                <div className="Comment_Section">
                  <div className="comment">
                    <FaRegComment fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRetweet fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <FaRegHeart fontSize="1.4rem"/>
                  </div>

                  <div className="comment">
                    <BsUpload fontSize="1.4rem"/>
                  </div>
                </div>
              </div>


            </div>
            
         
          <div className="Left_Sidebar_Area">
            <div className="search">
              <AiOutlineSearch fontSize="1.5rem" style={{borderRadius:"50%"}}/>
              <div className="search_input">
                <input type="search"placeholder="search twitter"/>
            </div>
          </div>
          <br></br>
          <div className="Container">
            <div className="Trends">
              <div className="Trenda_4u">
                Trends for you
              </div>
              <div className="Setting_icon">
                <BsGear fontSize="1.5rem" color="#1DA1F2"/>
              </div>
            </div>
            <div className="Trending_worldwide">
              <div className="Trending_show">
                Trending Worldwide 
              </div>
              <div className="tag">
                #WorldNews
              </div>
              <div className="tweet_people">
                125k
              </div>
              <div className="Tweets">
                5094 people are tweeting this 
              </div>
               </div>
               <div className="Trending_worldwide">
              <div className="Trending_show">
                Trending Worldwide 
              </div>
              <div className="tag">
                #KGF
              </div>
              <div className="tweet_people">
                1258k
              </div>
              <div className="Tweets">
                9582k people are tweeting this 
              </div>
               </div>
               <div className="Trending_worldwide">
              <div className="Trending_show">
                Trending Worldwide 
              </div>
              <div className="tag">
                #Online Marketing
              </div>
              <div className="tweet_people">
                180k
              </div>
              <div className="Tweets">
                7000 people are tweeting this 
              </div>
               </div>
               <div className="Trending_worldwide">
              <div className="Trending_show">
                Trending Worldwide 
              </div>
              <div className="tag">
                #Ipl
              </div>
              <div className="tweet_people">
                12554k
              </div>
              <div className="Tweets">
                10000 people are tweeting this 
              </div>
               </div>
          </div>


        </div>
      </div>
  </div>



      );
}

export default App;
[README.md](https://github.com/Girishgithub123/.github.io/files/8803633/README.md)
