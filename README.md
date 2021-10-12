# index.html
<!DOCTYPE html>  
<html>  
   <head> 
        
        <meta charset = "utf-8"> 
        <title>HJRS | HEC </title> 
        
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
        <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs    /font-awesome/4.7.0/css/font-awesome.min.css">
     
        <link rel="stylesheet" type="text/css" href="./style.css">
        
    <style>
        body {font-family: "Lato", sans-serif}
        .mySlides {display: none}

        
    </style>

    </head> 
       <header role = "banner"> 
        <style>
            
            .myDiv {
                background-color: white; 
                
                text-align: center;
                display:flex;
                flex-direction: row;
            }
            
            .myDiv1 {
                background-color: white; 
                
                text-align: center;
            }

            .myDiv2 {
                background-color: white; 
                
                text-align: right;
                float: right;
            }
            .myDiv {
                background-color: none; 
                
                text-align: center;
                display:flex;
                flex-direction: row;
            }
            
            #ABC {
                background-color:  #d5d8dc ;
            }
            
            #ABC1 {
                background-color: #82e0aa;
            }

        </style>  
    
    </header> 
    <body> 

       
        <div class="myDiv">
            <section >
                <input type="submit" value="HJRS ">
                HEC Journals <br>Recognition System 
            </section>
            
            
            <div class="myDiv2" > 
                <section >
                    <form action="/action_page.php">
                        <input type="submit" value="Journal Search ">
                        <input type="submit" value="Discipline-wise-search. ">
                        <input type="submit" value="About HJRS">
                        <input type="submit" value="FAQs">
                        <label for="Years">For Years:</label>
                            <select name="Year" id="year">
                                <option value="2021-22">2021-22</option>
                                <option value="2020-21">2020-21</option>
                                
                            </select>

                    </form>
            </div>   
            
        </div>
                
        
        <div class="myDiv" >
            <section>
                <div style="background-image: url('images/background.jpg');"> 
                <h2>Journals Search</h2>
                <section>
                    <div class="myDiv3" > 
                        <input type="submit" value="Journal Name ">
                        <input type="submit" value="ISSN ">
                    </div>

                    <input id="searchbar" onkeyup="search_animal()" type="text" name="search" placeholder="Type..">
                    <input type="submit" value="Find Journal">
                </section>
            
        
                <p>HJRS 2021-22 is applicable from July 01, 2021 to June 30, 2022. However, in following conditions, journal shall be treated as automatically de-recognized from the date of such discontinuation/removal if even present in HJRS. • Discontinued from Scopus (if only indexed in Scopus) • Discontinued from Web of Science (if only indexed in Web of Science) • Discontinued from both i.e. Web of Science and Scopus (if indexed in both) • Placed in Directory of Open Access Journals (DOAJ) removed list • Placed in Australian Business Dean Council (ABDC) removed list </p>
            </section>
        </div>

        <div class="myDiv1">
        <section>
            <h2>What is HJRS</h2>
            <p>A collection of research journals that are categorized into three different categories – W, X and Y -- within their respective knowledge areas on the basis of a number of internationally benchmarked and recognized parameters that measure the quality of a journal. The relative position and category of each journal is computed by a proprietary algorithm that is designed with the objective of promoting quality research across various disciplines. 
            </p>
        </section>

        </div>
        
        <div class="myDiv">
            <section>
                <img src="images/1.png" >
                <h2>Unique Algorithm </h2>
                <p>HJRS uses a novel Journal Prestige Index (JPI) measure which is calculated as a function of a journal's internationally benchmarked and recognized prestige parameters. The relative thresholds, decided by the respective scientific review panel of HEC, on JPI are used to classify Journals into W, X or Y categories. All six factors are given equal weight to ensure that no bias is introduced towards any single factor.</p>
            </section>
  
            <section>
                <img src="images/2.png" >
                <h2>Multidisciplinary </h2>
                <p>HJRS includes all the subject areas and sub-categories according to JACS. This provides precise and fine-grained positioning of a journal at two different levels: within a top-level subject area and different sub-categories within a top-level subject area. As a result, the quality parameters that associate a bias with any subject area are normalized relative to the parameters of the journals of a subject area.</p>
            </section>
            
            <section>
                <img src="images/3.png" >
                <h2>Transparency </h2>
                <p>HJRS reports raw and the percentile score of parameters and Journal Prestige Index (JPI) that are used for calculating the relative position of a journal to ensure transparency in assigning a category and medallion to a journal. The relative scores allow researchers to compare the quality of a journal in a Subject area and its associated sub-categories with the respective journals of the same area. </p>
            </section>
            
        </div>
        
        <div class="myDiv">
             <section id="ABC">
                
                <h2>HJRS Categories </h2>
                <p>HJRS categorizes a research journal into three categories – W, X and Y-- where W is the highest recognized category followed by X and Y within each subject area and its associated sub-categories.</p>
                <img src="images/Screenshot from 2021-10-06 20-23-08.png" >
            </section>
            
            <img src="images/Screenshot from 2021-10-06 18-51-01.png" >
        </div>
            
        <footer class="w3-container w3-padding-64 w3-center w3-opacity w3-light-grey w3-xlarge">

            <div class="myDiv" >
                <section>
                    
                    <p>Developed & Maintained by  </p>
                    <img src="images/Screenshot from 2021-10-06 23-41-30.png" >
        
                </section>
            </div>

            
            <p class="w3-medium">Created by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">MUHAMMAD ZEESHAN</a></p>
        </footer>



    </body> 
</html>
