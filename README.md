<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Game Press Kit</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        .container {
            padding: 2rem;
            max-width: 800px;
            margin: auto;
        }
        h1, h2 {
            color: #444;
        }
        .section {
            margin-bottom: 2rem;
        }
        .btn {
            display: inline-block;
            padding: 0.5rem 1rem;
            color: #fff;
            background: #007BFF;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 1rem;
        }
        .btn:hover {
            background: #0056b3;
        }
        img {
            max-width: 100%;
            height: auto;
            margin-bottom: 1rem;
        }
		
		.image-container {
			display: grid;
			grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
			gap: 10px;
		}
		
		.image-container img {
			width: 100%;
			height: auto;
			object-fit: cover;
			border-radius: 8px;
		}		





		.video-grid {
			display: grid;
			grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
			gap: 16px;
		}
		
		.video-item {
			position: relative;
			width: 100%;
			height: 0;
			padding-bottom: 56.25%; /* This ensures a 16:9 aspect ratio */
			overflow: hidden;
		}
		
		.video-item video {
			position: absolute;
			top: 0;
			left: 0;
			width: 100%;
			height: 100%;
			object-fit: cover;
		}

    </style>
</head>
<body>
    <header>
        <h1>Thrack-The-Fox Press Kit</h1>
    </header>
    <div class="container">
        <div class="section">
            <h2>About The Fox</h2>
            <p>"Thrack The Fox" is an upcoming 3D open-world adventure game developed collaboratively by TPSG (TrentPattersonStudioGaming) and Godway Games. Players will control Thrack, an anthropomorphic fox equipped with a sword, hammer, and bow, embarking on a quest for treasure in a vibrant, chaotic world. The game features a variety of unhinged characters, including dragons, parrots, dogs, lions, and beavers, each contributing to the game's rich narrative. While our protaganist finds himself in a world that's gone mad for treasure.</p>
        </div>
		<div class="image-container">
			<img src="Ga8bzkoXcAAChkC.jpg" alt="Screenshot">
			<img src="Ga18IFQXcAALOac.png" alt="Screenshot">
			<img src="GcDkUWMXcAA1RcU.png" alt="Screenshot">
			<img src="GgemHNoWEAAFJp8.png" alt="Screenshot">
			<img src="GN5_2HFWgAABNAD.png" alt="Screenshot">
			<img src="GNwO7JAXQAAZ2ot.png" alt="Screenshot">
			<img src="GO3_Ey_XgAAT9Oe.png" alt="Screenshot">
			<img src="GO37LyFWcAAOvQU.png" alt="Screenshot">
			<img src="GO37yyEXMAAG8-u.png" alt="Screenshot">
			<img src="GO37yyEXMAAG8-u.png" alt="Screenshot">
			<img src="GO38dYZWoAE4ZTj.png" alt="Screenshot">
			<img src="GO39XzXXkAABAJi.png" alt="Screenshot">
			<img src="GPqZ7tsXsAA5s3S.png" alt="Screenshot">
			<img src="GPVkOWqXAAAzkOY.png" alt="Screenshot">
			<img src="GPXOGO-WcAAt2v-.png" alt="Screenshot">
			<img src="GRoGesVagAAqBRR.png" alt="Screenshot">			
					
		</div>
		
		<script>
			document.querySelectorAll('.image-container img').forEach(img => {
				img.onload = () => {
					const ratio = img.naturalWidth / img.naturalHeight;
		
					if (ratio > 1.2) {
						img.style.aspectRatio = '16 / 9'; // Wide
					} else if (ratio < 0.8) {
						img.style.aspectRatio = '3 / 4'; // Tall
					} else {
						img.style.aspectRatio = '1 / 1'; // Square
					}
				};
			});
		</script>		
		
        <div class="section">
			<h3>Test Reels</h3>
			<div class="video-grid">
				<div class="video-item">
					<video autoplay loop muted>
						<source src="ConvertThrackSPrint.mp4" type="video/mp4">
						Your browser does not support the video tag.
					</video>
				</div>
				<div class="video-item">
					<video autoplay loop muted>
						<source src="CRABBOKI.mp4" type="video/mp4">
						Your browser does not support the video tag.
					</video>
				</div>
				<div class="video-item">
					<video autoplay loop muted>
						<source src="crumplersphere.mp4" type="video/mp4">
						Your browser does not support the video tag.
					</video>
				</div>
				<div class="video-item">
					<video autoplay loop muted>
						<source src="DYNAMICINVENTORY.mp4" type="video/mp4">
						Your browser does not support the video tag.
					</video>
				</div>
				<div class="video-item">
					<video autoplay loop muted>
						<source src="FlowersTest01.mp4" type="video/mp4">
						Your browser does not support the video tag.
					</video>
				</div>	
				<div class="video-item">
					<video autoplay loop muted>
						<source src="GWAYENDBOSSTHRACK.mp4" type="video/mp4">
						Your browser does not support the video tag.
					</video>
				</div>			
				<div class="video-item">
					<video autoplay loop muted>
						<source src="PauseTestThrack.mp4" type="video/mp4">
						Your browser does not support the video tag.
					</video>
				</div>						
				<div class="video-item">
					<video autoplay loop muted>
						<source src="scastle.mp4" type="video/mp4">
						Your browser does not support the video tag.
					</video>
				</div>										
				<div class="video-item">
					<video autoplay loop muted>
						<source src="SceneTransitioningTestThrack.mp4" type="video/mp4">
						Your browser does not support the video tag.
					</video>
				</div>		
				<div class="video-item">
					<video autoplay loop muted>
						<source src="ScrollCamMenu.mp4" type="video/mp4">
						Your browser does not support the video tag.
					</video>
				</div>		
				<div class="video-item">
					<video autoplay loop muted>
						<source src="SkeletonAdGodway.mp4" type="video/mp4">
						Your browser does not support the video tag.
					</video>
				</div>					
				<div class="video-item">
					<video autoplay loop muted>
						<source src="thrackbutcherfilm.mp4" type="video/mp4">
						Your browser does not support the video tag.
					</video>
				</div>						
			</div>
        </div>
		<style>

		.video-item {
			position: relative;
			width: 100%;
			padding-bottom: 56.25%; /* 16:9 aspect ratio */
			overflow: hidden;
			background: #000; /* Background color for better contrast */
		}
		
		.custom-video {
			position: absolute;
			top: 0;
			left: 0;
			width: 100%;
			height: 100%;
			object-fit: cover;
		}
		
		.audio-controls {
			display: flex;
			flex-direction: column;
			align-items: center;
			margin-top: 10px;
			width: 100%;
		}
		
		.play-pause-btn {
			padding: 8px 16px;
			font-size: 16px;
			cursor: pointer;
			background-color: #444;
			color: #fff;
			border: none;
			border-radius: 4px;
			margin-bottom: 8px;
		}
		
		.time-bar {
			width: 80%;
			margin-bottom: 10px;
		}
		
		.volume-controls {
			display: flex;
			align-items: center;
		}
		
		.mute-btn {
			padding: 8px;
			margin-right: 10px;
			cursor: pointer;
			background-color: #444;
			color: #fff;
			border: none;
			border-radius: 4px;
		}
		
		.volume-bar {
			width: 150px;
		}

		
		</style>
		<h3>Demo Music Samples</h3>
		<div class="video-item">
			<video id="music-video" class="custom-video">
				<source src="ThrackMusicShowOff.mp4" type="video/mp4">
				Your browser does not support the video tag.
			</video>
		</div>	
			<div class="audio-controls">
				<button id="play-pause" class="play-pause-btn">Play</button>
				<input type="range" id="time-bar" class="time-bar" value="0" step="1" min="0">
				<div class="volume-controls">
					<button id="mute-btn" class="mute-btn">Mute</button>
					<input type="range" id="volume-bar" class="volume-bar" value="100" min="0" max="100">
				</div>
			</div>
		
		<script>
		const video = document.getElementById('music-video');
		const playPauseBtn = document.getElementById('play-pause');
		const timeBar = document.getElementById('time-bar');
		const volumeBar = document.getElementById('volume-bar');
		const muteBtn = document.getElementById('mute-btn');
		
		// Play/Pause functionality
		playPauseBtn.addEventListener('click', () => {
			if (video.paused) {
				video.play();
				playPauseBtn.textContent = 'Pause';
			} else {
				video.pause();
				playPauseBtn.textContent = 'Play';
			}
		});
		
		// Update the time bar as the video plays
		video.addEventListener('timeupdate', () => {
			const currentTime = video.currentTime;
			const duration = video.duration;
			timeBar.value = (currentTime / duration) * 100;
		});
		
		// Sync video with time bar input
		timeBar.addEventListener('input', () => {
			const newTime = (timeBar.value / 100) * video.duration;
			video.currentTime = newTime;
		});
		
		// Mute/unmute functionality
		muteBtn.addEventListener('click', () => {
			video.muted = !video.muted;
			muteBtn.textContent = video.muted ? 'Unmute' : 'Mute';
		});
		
		// Volume control
		volumeBar.addEventListener('input', () => {
			video.volume = volumeBar.value / 100;
		});
		
		
		</script>		

		<style>
		.lowp2 {
			color: grey;
		}
		</style>
        <div class="section">
            <h2>Key Features</h2>
            <ul>
                <li><strong><h4>Dynamic Stylized Day-Night Cycle</strong></h4></li>
				<div class="lowp2">
				<p><strong>Experience the world change in real-time with a dynamic day-night cycle, time affects gameplay, puzzles, and player choice.</strong></p>
				</div>
                <li><strong><h4>Play as Thrack</strong></h4></li>
				<div class="lowp2">
				<p><strong>Embark on an epic adventure as Thrack, a large and well meaning but relatively unintelligent anthropomorphic fox with and a range of combat abilities, including swordplay, hammer strikes, and archery.</strong></p>
				</div>
                <li><strong><h4>Open-World Exploration</strong></h4></li>
				<div class="lowp2">
				<p><strong>Roam freely across a vibrant, chaotic and creative world of highly accentuated eccentric characters.</strong></p>
				</div>			
                <li><strong><h4>Modding Support</strong></h4></li>
				<div class="lowp2">
				<p><strong>Thrack the Fox includes a fully integrated Modding API, allowing players to interact with the game's assets directly from the console. <br> It also allows mod-creators to upload share their own content directly within the game.</strong></p>
				</div>
                <li><strong><h4>PlayStation 1-Style Graphics</strong></h4></li>
				<div class="lowp2">
				<p><strong>Enjoy a nostalgic, retro-inspired art style that evokes the feel of 90s-era games, as well as guarunteeing that mid-range systems will be able to render its gameplay.</strong></p>
				</div>				
                <li><strong><h4>Combination of Choreographed and dynamic Combat</strong></h4></li>
				<div class="lowp2">
				<p><strong>In Thrack The Fox combat is Choreographically animated to the game level itself so that enemies can interact seamlessly with eachother, while also providing a break from these patterns through more old fashioned means of dynamic ai. <br><br>In Thrack The Fox every enemy is at the technical level an individual rather than being copy pasted onto the level as we've come to expect from most titles. It is in this way that we hope to provide a dynamic puzzler style combat experience.</strong></p>
				</div>								
                <li><strong><h4>Portal To Unique Worlds From Hubs</strong></h4></li>
				<div class="lowp2">
				<p><strong>Thrack contains many worlds which can be portaled too from the primary world giving the environment a fantastical near-psychodelic atmosphere and feeling.</strong></p>
				</div>												
            </ul>
        </div>
		
		

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Popup with URLs</title>
    <style>
        /* Styles for the popup */
        .popup {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            justify-content: center;
            align-items: center;
            z-index: 999;
        }

        .popup-content {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            width: 300px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }

        .popup-content h2 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }

        .popup-content ul {
            list-style-type: none;
            padding: 0;
        }

        .popup-content ul li {
            margin: 10px 0;
        }

        .popup-content a {
            color: #007BFF;
            text-decoration: none;
        }

        .popup-content a:hover {
            text-decoration: underline;
        }

        .close-btn {
            position: absolute;
            top: 10px;
            right: 10px;
            font-size: 1.5em;
            cursor: pointer;
        }
    </style>
	
<style>
    /* Body & General Styling */
    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        margin: 0;
        padding: 0;
        background-color: #f4f4f9;
        color: #333;
    }

    header {
        background: #333;
        color: #fff;
        padding: 1rem;
        text-align: center;
    }

    .container {
        padding: 2rem;
        max-width: 800px;
        margin: auto;
    }

    h1, h2 {
        color: #444;
    }

    .section {
        margin-bottom: 2rem;
    }

    .btn {
        display: inline-block;
        padding: 0.5rem 1rem;
        color: #fff;
        background: #007BFF;
        text-decoration: none;
        border-radius: 5px;
        margin-top: 1rem;
    }

    .btn:hover {
        background: #0056b3;
    }

    img {
        max-width: 100%;
        height: auto;
        margin-bottom: 1rem;
    }

    .image-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 10px;
    }

    .image-container img {
        width: 100%;
        height: auto;
        object-fit: cover;
        border-radius: 8px;
    }

    .video-grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
        gap: 16px;
    }

    .video-item {
        position: relative;
        width: 100%;
        height: 0;
        padding-bottom: 56.25%; /* This ensures a 16:9 aspect ratio */
        overflow: hidden;
    }

    .video-item video {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

    /* Windows Button Styling */
    .button-container {
        position: relative;
        display: inline-block;
    }

    .windows-button {
        width: 220px;
        height: 45px;
        background-color: #0084ff;
        border-radius: 10px;
        display: flex;
        align-items: center;
        justify-content: center;
        cursor: pointer;
        transition: background-color 0.3s ease;
        padding: 0 15px; /* Adjusted padding for balance */
        font-size: 18px;
    }

    .windows-logo {
        font-size: 24px;
        color: white;
        margin-right: 10px; /* Logo to text space */
		align-items: center; /* Aligns the logo and text vertically */
		object-fit: contain;
    }

    .button-text {
        font-size: 18px;
        color: white;
        font-weight: bold;
    }

    .red-x {
        position: absolute;
        top: -10px;
        left: -10px;
        width: 100%;
        height: 100%;
        display: none;
        color: red;
        font-size: 70px;
        font-weight: bold;
        text-align: center;
        line-height: 120px;
        pointer-events: none;
    }

    .button-container:hover .red-x {
        display: block;
    }

    .windows-button:active {
        background-color: #0069c0;
    }

    /* Popup Styling */
    .popup {
        display: none;
        position: fixed;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        background-color: #333;
        color: white;
        padding: 20px;
        border-radius: 10px;
        font-size: 18px;
        font-weight: bold;
        box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
        //width: 300px; /* Set a fixed width for the popup */
        max-width: 10%; /* To ensure responsiveness */
		max-height: 10%; /* To ensure responsiveness */
        z-index: 9999;
        text-align: center;
    }

    .popup.show {
        display: block;
    }
</style>

  <style>
    /* Style for the popup */
    .popupx {
      display: none;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.5);
      z-index: 1000;
    }

    .popupx-content {
      position: relative;
      background-color: white;
      margin: 10% auto;
      padding: 20px;
      width: 60%;
      border-radius: 5px;
    }

    .close-btn {
      position: absolute;
      top: 10px;
      right: 10px;
      font-size: 20px;
      cursor: pointer;
    }
  </style>

	
</head>

		
		
        <div class="section">
            <h2>Download Assets</h2>
            <a href="press-assets.zip" class="btn">Download Press Kit</a><!--&nbsp; <a href="press-assets.zip" class="btn">Download Press Kit</a>--><div class="button-container">&nbsp; 
    <div class="btn" onclick="showPopup()">
        <div class="windows-logo">
            <img src="https://upload.wikimedia.org/wikipedia/commons/8/87/Windows_logo_-_2021.svg" alt="Windows Logo" style="display: float; width: 40px; height: 40px; justify-content: flex-start; display: flex;">
        <div class="button-text">Demo Disc</div> <!-- Text on the button -->
        </div>
        <div class="red-x">X</div>
    </div>
</div>
        </div>


<div id="popup" class="popup">Public Demo Not Yet Available</div>

<script>
    function showPopup() {
        // Show the popup with a delay to allow user to click
        setTimeout(function() {
            document.getElementById('popup').classList.add('show');
        }, 300);
    }

    // Close popup when clicked anywhere
    window.onclick = function(event) {
        if (!event.target.closest('.windows-button')) {
            document.getElementById('popup').classList.remove('show');
        }
    };
</script>		
	<div class="section">
	<h2>Progress</h2>
	<button class="btn" onclick="openPopup()">Progression Timeline</button>	<button class="btn" onclick="openPopup2()">General Timeline</button>
	</div>		


  <!-- The Popup -->
  <div class="popupx" id="popupx">
    <div class="popupx-content">
      <span class="close-btn" onclick="closePopup()">&times;</span>
      <!-- Embedding another webpage in the popup -->
      <iframe src="Progress.html" width="100%" height="400px" style="border: none;"></iframe>
    </div>
  </div>
  
  <!-- The Popup -->
  <div class="popupx" id="popupx2">
    <div class="popupx-content">
      <span class="close-btn" onclick="closePopup()">&times;</span>
      <!-- Embedding another webpage in the popup -->
      <iframe src="Timeline.html" width="100%" height="400px" style="border: none;"></iframe>
    </div>
  </div>  

  <script>
    // Function to open the popup
    function openPopup() {
      document.getElementById('popupx').style.display = 'block';
    }
    function openPopup2() {
      document.getElementById('popupx2').style.display = 'block';
    }
    function openPopup3() {
      document.getElementById('popupx3').style.display = 'block';
    }	
    // Function to close the popup
    function closePopup() {
      document.getElementById('popupx').style.display = 'none';
	  document.getElementById('popupx2').style.display = 'none';
	  document.getElementById('popupx3').style.display = 'none';	  
    }
  </script>
		
        <div class="section">
            <h2>Social Handles & Specialty Urls</h2>
            <!--<p>For inquiries, please contact: <a href="mailto:your-email@example.com">your-email@example.com</a></p>-->
        </div>
    <!-- Button to trigger popup -->
    <button class="btn" id="showPopupBtn" onclick="openPopup3()">Show URLs</button>

    <!-- Popup Box -->
<!--    <div id="popupBox" class="popup">
<!--        <div class="popup-content">
<!--            <!--<span class="close-btn" id="closePopupBtn">&times;</span>-->
<!--            <h2>Here are some useful URLs:</h2>
<!--            <ul>
<!--                <li><a href="https://www.example.com" target="_blank">Example 1</a></li>
                <li><a href="https://www.example2.com" target="_blank">Example 2</a></li>
                <li><a href="https://www.example3.com" target="_blank">Example 3</a></li>
            </ul>
        </div>
    </div>-->

  <!-- The Popup -->
  <div class="popupx" id="popupx3">
    <div class="popupx-content">
      <span class="close-btn" onclick="closePopup()">&times;</span>
      <!-- Embedding another webpage in the popup -->
      <iframe src="MediaHandles.html" width="100%" height="400px" style="border: none;"></iframe>
    </div>
  </div>  
	
    <script>
        // Get elements
        const popupBox = document.getElementById("popupBox");
        const showPopupBtn = document.getElementById("showPopupBtn");
        const closePopupBtn = document.getElementById("closePopupBtn");

        // Show popup when button is clicked
        showPopupBtn.addEventListener("click", function() {
            popupBox.style.display = "flex";
        });

        // Close popup when close button is clicked
        closePopupBtn.addEventListener("click", function() {
            popupBox.style.display = "none";
        });

        // Close popup when clicking outside the popup content
        window.addEventListener("click", function(event) {
            if (event.target === popupBox) {
                popupBox.style.display = "none";
            }
        });
    </script>
    </div>
</body>
</html>
