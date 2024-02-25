# This exercise deals with video related issues:

    1. Online Videos: Youtube/other site
        --> directly copy from the share embedded to html
        
        ### Example
            '''
            <iframe
          width="560"
          height="315"
          src="https://www.youtube.com/embed/vqXLGX0szIQ?si=7HKWKEUDRftkq5rA"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen
        ></iframe>


    2. Custom Videos: mp4/webm
        - webm isn't supported by old browser however, it is very small in size compared to mp4 so, fast loading.
        --> Webm can be converted from mp4

    ### Example
        '''
        <video
          src="../assets/videos/video-1@c.mp4"
          width="484"
          loop
          muted
          controls
          poster="../assets/images/video-poster.jpg"
        ></video>
