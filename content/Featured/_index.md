---
paige:
  color: "#e0bb46"
  style: |
    #paige-collections,
    #paige-sections,
    #paige-pages {
      display: none;
    }
---
<p>{{% paige/image alt="Landscape" breakpoints=true class="object-fit-contain" fetchpriority="high" loading="eager" process="webp" src="./images/Seafeaton.png" height="9rem" width="100%" %}}</p><br>
<center>Here you can find a collection of compilations where Seathasky's music has been featured on:</center><br>
<center><h4>(Albums are sorted by release date order)</h4></center>
<br>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Artist Page</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-image: url('/images/discog/releasebg.png'); 
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .artist-info {
            display: flex;
            align-items: center;
        }
        .artist-info img {
            max-width: 200px;
            height: auto;
            margin-right: 20px;
        }
        .artist-name {
            font-size: 24px;
            font-weight: bold;
        }
        .album-list {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: space-between;
        }
        .album {
            width: calc(33.33% - 20px);
            background-color: #fff;
            border: 0px solid #ccc;
            border-radius: 5px;
            padding: 10px;
            text-align: center;
            background-color: rgba(255, 255, 255, 0.1); 
        }
        .album img {
            max-width: 100%;
            height: auto;
        }
        .album-buy {
            font-size: 16px;
            font-weight: bold;
            margin: 10px 0;
        }
        .label {
            font-size: 16px;
            font-weight: bold;
            margin: 10px 0;
        }
        .album-link {
            color: #e0bb46;
            text-decoration: none;
          }
        .label-link {
            color: #e0bb46;
            font-size: 12px;
            text-decoration: none;
        }
        .album-link:hover {
            text-decoration: underline;
        }
        .album-text {
            font-size: 14px;
            margin: 10px 0;
          }
        .date-text {
            font-size: 12px;
            margin: 10px 0;
        }
            
  </style>
</head>
<body>
        <div class="album-list">
            <div class="album">
                <img src="/images/featuredimg/bymyside.jpg" alt="By My Side">
                <p class="album-text"><b>The River of Time Ep</b></p>
                <p class="date-text">Released on 08/25/2023</p>
                <p class="label"><a href="https://fokuzrecordings.com/" class="label-link">Fokuz Recordings</a></p>
                <p class="album-buy"><a href="https://www.beatport.com/release/the-river-of-time-ep/4083237" class="album-link">Listen / Buy</a></p>
            </div>
            <div class="album">
                <img src="/images/featuredimg/summervibes.jpg" alt="Summer Vibes">
                <p class="album-text"><b>Summer Vibes</b> | C. Recordings</p>
                <p class="date-text">Released on 07/24/2023</p>
                <p class="label"><a href="https://c-recordings.com/" class="label-link">C. Recordings</a></p>
                <p class="album-buy"><a href="https://crecordings.bandcamp.com/album/summer-vibes" class="album-link">Listen / Buy</a></p>
            </div>      
            <div class="album">
                <img src="/images/featuredimg/memories2.jpg" alt="Summer Vibes">
                <p class="album-text"><b>Summer Vibes</b></p>
                <p class="date-text">Released on 01/20/2023</p>
                <p class="label"><a href="https://c-recordings.com/" class="label-link">C. Recordings</a></p>
                <p class="album-buy"><a href="https://www.junodownload.com/products/memories-2/5908955-02/" class="album-link">Listen / Buy</a></p>
            </div>    
             <div class="album">
                <img src="/images/featuredimg/focuzrecap.jpg" alt="Fokuz Recap 2022">
                <p class="album-text"><b>Fokuz Recap 2022</b></p>
                <p class="date-text">Released on 12/23/2022</p>
                <p class="label"><a href="https://fokuzrecordings.com/" class="label-link">Fokuz Recordings</a></p>
                <p class="album-buy"><a href="https://fokuzrecordings.bandcamp.com/album/fokuz-recap-2022/" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/usavsukaut.jpg" alt="USA VS UK">
                <p class="album-text"><b>USA vs UK</b></p>
                <p class="date-text">Released on 11/8/2022</p>
                <p class="label"><a href="https://www.liquiddnb4autism.org/" class="label-link">Liquid DNB 4 Autism, Inc.</a></p>
                <p class="album-buy"><a href="https://www.liquiddnb4autism.org/shop" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/offworldtransmv9.jpg" alt="OWT9">
                <p class="album-text"><b>Offworld Transmissions Vol. 9</b></p>
                <p class="date-text">Released on 09/19/2022</p>
                <p class="label"><a href="https://offworldrecordings.bandcamp.com/" class="label-link">Offworld Recordings</a></p>
                <p class="album-buy"><a href="https://offworldrecordings.bandcamp.com/album/offworld-transmissions-volume-9-offworld105" class="album-link">Listen / Buy</a></p>
            </div>  
             <div class="album">
                <img src="/images/featuredimg/watchatnight.jpg" alt="Watch the night">
                <p class="album-text"><b>Get Away / Watch at Night</b></p>
                <p class="date-text">Released on 01/28/2022</p>
                <p class="label"><a href="https://celsiusrecordings.bandcamp.com/" class="label-link">Celsius Recordings</a></p>
                <p class="album-buy"><a href="https://celsiusrecordings.bandcamp.com/album/get-away-watch-at-night" class="album-link">Listen / Buy</a></p>
            </div> 
             <div class="album">
                <img src="/images/featuredimg/fkuzrecap2.jpg" alt="Fokuz Recap 2021">
                <p class="album-text"><b>Best of Fokuz 2021</b></p>
                <p class="date-text">Released on 12/17/2021</p>
                <p class="label"><a href="https://fokuzrecordings.com/" class="label-link">Fokuz Recordings</a></p>
                <p class="album-buy"><a href="https://fokuzrecordings.bandcamp.com/album/best-of-fokuz-2021" class="album-link">Listen / Buy</a></p>
            </div>  
            <div class="album">
                <img src="/images/featuredimg/zerogravep.jpg" alt="Zero Gravity Remix EP">
                <p class="album-text"><b>Zero Gravity Remix EP</b></p>
                <p class="date-text">Released on 12/21/2020</p>
                <p class="label"><a href="https://offworldrecordings.bandcamp.com/" class="label-link">Offworld Recordings</a></p>
                <p class="album-buy"><a href="https://www.beatport.com/release/zero-gravity-remix-ep/955389" class="album-link">Listen / Buy</a></p>
            </div>  
            <div class="album">
                <img src="/images/featuredimg/bestof2020.jpg" alt="Best of 2020">
                <p class="album-text"><b>Celsius Best of 2020</b></p>
                <p class="date-text">Released on 12/21/2020</p>
                <p class="label"><a href="https://celsiusrecordings.bandcamp.com/" class="label-link">Celsius Recordings</a></p>
                <p class="album-buy"><a href="https://www.beatport.com/release/celsius-best-of-2020/3476608" class="album-link">Listen / Buy</a></p>
            </div> 
             <div class="album">
                <img src="/images/featuredimg/offworltransv8.jpg" alt="Offworld Transmissions Vol. 8 ">
                <p class="album-text"><b>Offworld Transmissions Vol. 8</b></p>
                <p class="date-text">Released on 10/12/2020</p>
                <p class="label"><a href="https://offworldrecordings.bandcamp.com/" class="label-link">Offworld Recordings</a></p>
                <p class="album-buy"><a href="https://www.beatport.com/release/offworld-transmissions-volume-8/3142795" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/ss001.png" alt="SS 001">
                <p class="album-text"><b>Study Sounds 001</b></p>
                <p class="date-text">Released on 09/11/2020</p>
                <p class="label"><a href="https://www.traxsource.com/label/42336/hot-q" class="label-link">Hot-Q (Label Worx)</a></p>
                <p class="album-buy"><a href="https://www.amazon.com/The-Force-KARU-Remix/dp/B08GYSBKXK" class="album-link">Listen / Buy</a></p>
            </div>  
            <div class="album">
                <img src="/images/featuredimg/losingfaith.jpg" alt="Jail Break EP">
                <p class="album-text"><b>Matt View - Jail Break EP</b></p>
                <p class="date-text">Released on 08/10/2020</p>
                <p class="label"><a href="https://fokuzrecordings.com/" class="label-link">Fokuz Recordings</a></p>
                <p class="album-buy"><a href="https://www.beatport.com/release/jail-break-ep/3064491" class="album-link">Listen / Buy</a></p>
            </div>  
             <div class="album">
                <img src="/images/featuredimg/scenesep.jpg" alt="Scenes">
                <p class="album-text"><b>Matt View - Scenes EP</b></p>
                <p class="date-text">Released on 07/06/2020</p>
                <p class="label"><a href="https://celsiusrecordings.bandcamp.com/" class="label-link">Celsius Recordings</a></p>
                <p class="album-buy"><a href="https://www.beatport.com/release/scenes-ep/2999535" class="album-link">Listen / Buy</a></p>
            </div> 
             <div class="album">
                <img src="/images/featuredimg/fragmentsoflove.jpg" alt="Fragments of Love EP">
                <p class="album-text"><b>Fragments of Love EP</b></p>
                <p class="date-text">Released on 06/01/2020</p>
                <p class="label"><a href="https://rotationuk.bandcamp.com/" class="label-link">Rotation Deep UK</a></p>
                <p class="album-buy"><a href="https://rotationuk.bandcamp.com/album/fragments-of-love-ep" class="album-link">Listen / Buy</a></p>
            </div> 
            <div class="album">
                <img src="/images/featuredimg/dnbanthemv7.jpg" alt="DNB Anthems v7">
                <p class="album-text"><b>DNB Anthems Vol. 7</b></p>
                <p class="date-text">Released on 03/27/2020</p>
                <p class="label"><a href="https://www.discogs.com/label/530606-Nothing-But" class="label-link">Nothing But.. (Label Worx)</a></p>
                <p class="album-buy"><a href="https://www.junodownload.com/products/nothing-but-drum-bass-anthems-vol/4491016-02/" class="album-link">Listen / Buy</a></p>
            </div> 
             <div class="album">
                <img src="/images/featuredimg/techmosphere3.jpg" alt="Techmosphere .03 LP">
                <p class="album-text"><b>Techmosphere .03 LP</b></p>
                <p class="date-text">Released on 11/15/2019</p>
                <p class="label"><a href="https://scientificrecords.bandcamp.com/" class="label-link">Scientific Records</a></p>
                <p class="album-buy"><a href="https://www.amazon.com/Techmosphere-Actraiser-Electrosoul-Seathasky-Hiddenwave/dp/B09GW35285" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/retrospecview3.jpg" alt="RV3">
                <p class="album-text"><b>Retrospective View 3</b></p>
                <p class="date-text">Released on 08/05/2019</p>
                <p class="label"><a href="https://c-recordings.com/" class="label-link">C. Recordings</a></p>
                <p class="album-buy"><a href="https://www.deezer.com/us/album/103837982" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/chillingoncouchv3.jpg" alt="Chill on the Couch 3">
                <p class="album-text"><b>Chilling on the Couch 3 LP</b></p>
                <p class="date-text">Released on 9/07/2018</p>
                <p class="label"><a href="https://scientificrecords.bandcamp.com/" class="label-link">Scientific Records</a></p>
                <p class="album-buy"><a href="https://scientificrecords.bandcamp.com/album/sci025-chilling-on-the-couch-03-lp" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/offworldtranv7.jpg" alt="OWT7">
                <p class="album-text"><b>Offworld Transmissions Vol. 7</b></p>
                <p class="date-text">Released on 07/23/2018</p>
                <p class="label"><a href="https://offworldrecordings.bandcamp.com/" class="label-link">Offworld Recordings</a></p>
                <p class="album-buy"><a href="https://offworldrecordings.bandcamp.com/album/offworld-transmissions-volume-7-offworld062" class="album-link">Listen / Buy</a></p>
            </div>
            <div class="album">
                <img src="/images/featuredimg/offworldanth1.jpg" alt="OW Anthology 1">
                <p class="album-text"><b>Anthology One</b></p>
                <p class="date-text">Released on 08/21/2017</p>
                <p class="label"><a href="https://offworldrecordings.bandcamp.com/" class="label-link">Offworld Recordings</a></p>
                <p class="album-buy"><a href="https://offworldrecordings.bandcamp.com/album/offworld-anthology-one-offworld057" class="album-link">Listen / Buy</a></p>
            </div>
            <div class="album">
                <img src="/images/featuredimg/techmospherev2.jpg" alt="Techmosphere .02 LP">
                <p class="album-text"><b>Techmosphere .02 LP</b></p>
                <p class="date-text">Released on 07/14/2017</p>
                <p class="label"><a href="https://scientificrecords.bandcamp.com/" class="label-link">Scientific Records</a></p>
                <p class="album-buy"><a href="https://scientificrecords.bandcamp.com/album/sci023-techmosphere-02-lp" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/offworldtransv6.jpg" alt="OWT6">
                <p class="album-text"><b>Offworld Transmissions Vol. 6</b></p>
                <p class="date-text">Released on 07/11/2016</p>
                <p class="label"><a href="https://offworldrecordings.bandcamp.com/" class="label-link">Offworld Recordings</a></p>
                <p class="album-buy"><a href="https://offworldrecordings.bandcamp.com/album/offworld-transmissions-volume-6-offworld050" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/deepstep.jpg" alt="Deepstep">
                <p class="album-text"><b>Deepstep 01 LP</b></p>
                <p class="date-text">Released on 05/06/2016</p>
                <p class="label"><a href="https://scientificrecords.bandcamp.com/" class="label-link">Scientific Records</a></p>
                <p class="album-buy"><a href="https://scientificrecords.bandcamp.com/album/sci020-deepstep-01-lp" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/techmosphere.jpg" alt="Techmo 1">
                <p class="album-text"><b>Techmosphere .01</b></p>
                <p class="date-text">Released on 07/06/2015</p>
                <p class="label"><a href="https://scientificrecords.bandcamp.com/" class="label-link">Scientific Records</a></p>
                <p class="album-buy"><a href="https://scientificrecords.bandcamp.com/album/sci018-techmosphere-01-lp" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/chillingoncouch.jpg" alt="COTC1">
                <p class="album-text"><b>Chilling on the Couch LP</b></p>
                <p class="date-text">Released on 10/17/2014</p>
                <p class="label"><a href="https://scientificrecords.bandcamp.com/" class="label-link">Scientific Records</a></p>
                <p class="album-buy"><a href="https://scientificrecords.bandcamp.com/album/sci016-chilling-on-the-couch-01-lp" class="album-link">Listen / Buy</a></p>
            </div>
            <div class="album">
                <img src="/images/featuredimg/offworldtransv4.jpg" alt="OWT4">
                <p class="album-text"><b>Offworld Transmissions Vol. 4</b></p>
                <p class="date-text">Released on 03/17/2014</p>
                <p class="label"><a href="https://offworldrecordings.bandcamp.com/" class="label-link">Offworld Recordings</a></p>
                <p class="album-buy"><a href="https://offworldrecordings.bandcamp.com/album/ofw034-transmissions-volume-4" class="album-link">Listen / Buy</a></p>
            </div>
            <div class="album">
                <img src="/images/featuredimg/differentshores.jpg" alt="Different SHoes">
                <p class="album-text"><b>Different Shores</b></p>
                <p class="date-text">Released on 12/31/2012</p>
                <p class="label"><a href="https://offworldrecordings.bandcamp.com/" class="label-link">Offworld Recordings</a></p>
                <p class="album-buy"><a href="https://offworldrecordings.bandcamp.com/album/ofw025-different-shores-compilation" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/backintheday.jpg" alt="Back in the Day">
                <p class="album-text"><b>Dan Guidance - Back In The Day</b></p>
                <p class="date-text">Released on 12/31/2012</p>
                <p class="label"><a href="https://www.beatport.com/label/connessione-recordings/28045" class="label-link">Connessione Recordings</a></p>
                <p class="album-buy"><a href="https://www.beatport.com/release/back-in-the-day/1017529" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/conneentangle.jpg" alt="Entanglement">
                <p class="album-text"><b>Entanglement Series Vol. 1</b></p>
                <p class="date-text">Released on 12/15/2012</p>
                <p class="label"><a href="https://www.beatport.com/label/connessione-recordings/28045" class="label-link">Connessione Recordings</a></p>
                <p class="album-buy"><a href="https://www.beatport.com/release/entanglement-series-vol-1/1001900" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/intodarkness.jpg" alt="Into the Darkness EP">
                <p class="album-text"><b>Into the Darkness EP</b></p>
                <p class="date-text">Released on 11/30/2012</p>
                <p class="label"><a href="https://rotationuk.bandcamp.com/" class="label-link">Rotation UK</a></p>
                <p class="album-buy"><a href="https://rotationuk.bandcamp.com/album/into-the-darkness-remix-ep" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/welcometochat.jpg" alt="Welcome To Chatsworth">
                <p class="album-text"><b>Welcome To Chatsworth</b></p>
                <p class="date-text">Released on 10/05/2012</p>
                <p class="label"><a href="https://rotationuk.bandcamp.com/" class="label-link">Rotation UK</a></p>
                <p class="album-buy"><a href="https://rotationuk.bandcamp.com/album/welcome-to-chatsworth-lp" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/conneconnections.jpg" alt="Connessione Connections">
                <p class="album-text"><b>Connessione Connections</b></p>
                <p class="date-text">Released on 09/06/2012</p>
                <p class="label"><a href="https://www.beatport.com/label/connessione-recordings/28045" class="label-link">Connessione Recordings</a></p>
                <p class="album-buy"><a href="https://www.beatport.com/release/connessione-connections-volume-1/959843" class="album-link">Listen / Buy</a></p>
            </div>
             <div class="album">
                <img src="/images/featuredimg/crossfireep.png" alt="Crossfire EP">
                <p class="album-text"><b>Crossfire EP</b></p>
                <p class="date-text">Released on 6/4/2012</p>
                <p class="label"><a href="https://mac2records.bandcamp.com/" class="label-link">Mac2 Recordings</a></p>
                <p class="album-buy"><a href="https://mac2records.bandcamp.com/album/crossfire-ep-session-1" class="album-link">Listen / Buy</a></p>
            </div>
              <div class="album">
                <img src="/images/featuredimg/offworldtransv2.jpg" alt="OWT2">
                <p class="album-text"><b>Offworld Transmissions Vol. 2</b></p>
                <p class="date-text">Released on 05/07/2012</p>
                <p class="label"><a href="https://offworldrecordings.bandcamp.com/" class="label-link">Offworld Recordings</a></p>
                <p class="album-buy"><a href="https://offworldrecordings.bandcamp.com/album/ofw19-offworld-transmissions-volume-2" class="album-link">Listen / Buy</a></p>
            </div>
              <div class="album">
                <img src="/images/featuredimg/missingfrag.jpg" alt="Missing Fragments">
                <p class="album-text"><b>Missing Fragments</b></p>
                <p class="date-text">Released on 4/23/2012</p>
                <p class="label"><a href="https://absysrec.bandcamp.com/" class="label-link">Absys Records</a></p>
                <p class="album-buy"><a href="https://absysrec.bandcamp.com/album/missing-fragments" class="album-link">Listen / Buy</a></p>
            </div>
            <div class="album">
                <img src="/images/featuredimg/defofthedeep2.jpg" alt="DOTD2">
                <p class="album-text"><b>Definitions Of The Deep II</b></p>
                <p class="date-text">Released on 1/29/2012</p>
                <p class="label"><a href="https://rotationuk.bandcamp.com/" class="label-link">Rotation UK</a></p>
                <p class="album-buy"><a href="https://rotationuk.bandcamp.com/album/definitions-of-the-deep-ii-lp" class="album-link">Listen / Buy</a></p>
            </div>
            <div class="album">
                <img src="/images/featuredimg/offworldtranv1.jpg" alt="OWT1">
                <p class="album-text"><b>Offworld Transmissions Vol. 1</b></p>
                <p class="date-text">Released on 09/20/2010</p>
                <p class="label"><a href="https://offworldrecordings.bandcamp.com/" class="label-link">Offworld Recordings</a></p>
                <p class="album-buy"><a href="https://offworldrecordings.bandcamp.com/album/ofw07-transmissions-vol-1" class="album-link">Listen / Buy</a></p>
            </div>
        </div>
    </div>
</body>
</html>






