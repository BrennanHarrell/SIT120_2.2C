<template>
  <div class="nav">
  </div>

  <h1 class="header">
    Introduction to Responsive Web Apps
    <IMG class="displayed" alt="Deakin img-deakin-logo-white-desktop" src="https://masternav.sync.deakin.edu.au/assets/img-deakin-logo-white-desktop.svg"/>
  </h1>

        <section id="content">
            <h2 style="text-align: center;">Creating Responsive Web Apps</h2>
            <p style="text-align: center;">This is my web page to showcase all of my html and css programming. <br>
            Checkout the following links which will showcase some of my other works and signup to view more as well as stay in the loop with what I am working on.</p>
        </section>

          <p style="text-align:center">
           
          </p>

          <table class="table">
            <tr>
              <th>My Github</th> <th>My videos</th>
            </tr>
            <tr>
              <td>
               <a href="https://github.com/BrennanHarrell?tab=repositories" class="btn">Github Link</a>
              </td> 
              <td>
                <a href="https://video.deakin.edu.au/media/t/1_epxiydms" class="btn">Airdeakin Link</a>
              </td>
            </tr>            
          </table>

          <form class="form">
            <h3>Sign in to view more</h3>
            <label for="fname">First name:</label><br>
            <input type="text" id="fname" name="fname" placeholder="First name"><br>
            <label for="lname">Last name:</label><br>
            <input type="text" id="lname" name="lname" placeholder="Last name"><br>
            <label for="lname">Student ID:</label><br>
            <input type="text" id="idnum" name="idnum" placeholder="s11223344">
            <br><br>
            <input type="submit" value="Submit">
          </form>

          <footer style="font-size: 20pt;">
              Stay Tuned
          </footer>
</template>

<script>


export default {
  name: 'HomeView',
  components: {
  }
}
</script>
