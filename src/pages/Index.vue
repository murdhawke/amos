<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-16 mt-8">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-left">
        <div class="leading-tight">Product Support, Javascript Enthusiast, Tech Excellence</div>
        <div class="text-green-700 leading-tight">I love tech!</div>
      </div>
      <div class="mt-8 sm:mt-0">
        <g-image immediate=true src="../../static/developer.svg" alt="hero" class="mx-auto sm:mx-0" />
      </div>
    </div> <!-- end hero -->

    <div class="container-inner mx-auto">
      <p class="text-lg sm:text-xl">
        Hey,  I am Amos.  Nice to meet you!<br>
           I love working with cross-platform tools such as Vue.js, Google App Script, Zappier and Slack to build business intelligence integrations. <br>I am  also interested in modern web development technologies such as Wordpress, JAMStack and Node.js.
</p>

      <div class="flex justify-between items-center py-6">
        <div class="w-full sm:w-1/2 px-8 py-8 sm:py-0">
          <g-image src="../../static/integrations.svg" alt="browser" />
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div id="projects" style="position: relative; top: -40px; left: 0"/>
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative">
        <h2 class="font-bold mb-6">Here are some projects I've worked on:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <ul class="text-lg sm:text-xl space-y-6">
          <li class="checkmark">
            <div><b>Farmika</b></div>
            <div class="text-lg text-gray-600">A web solution that makes farming easier.</div>
          </li>
          <li class="checkmark">
            <div><b>Covidata</b></div>
            <div class="text-lg text-gray-600">Get the latest information on Covid-19 infections, vaccinations and curve.</div>
          </li>
          <li class="checkmark">
            <div><b>Foota</b></div>
            <div class="text-lg text-gray-600">Get the latest scores on every live game.</div>
          </li>
          <li class="checkmark">
            <div><b>Angani</b></div>
            <div class="text-lg text-gray-600">Know the weather </div>
          </li>

        </ul>
      </div> <!-- end projects -->
    </div>

    <div class="overflow-x-hidden border-gray-200 border-b">
      <div id="about" style="position: relative; top: -40px; left: 0"/>
      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <h2 class="font-bold mb-6">Get to know me:</h2>

        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-8">
          <div><g-image src="../../static/hulk.png" alt="avatar" class="w-32 h-52 rounded-full mb-8 lg:mb-0" /></div>
          <div class="flex-1 text-lg sm:text-xl ml-6">I love music, hiking and Star Wars.  In my spare time, I watch football and try to learn something new.  Hulk is my favorite superhero(Hail Marvel!)</div>
          <div class="flex-2 ml-6">
          </div>
            <a href="https://docs.google.com/uc?export=download&id=1ttCzz4ge2u_PkidbgCqCt1XDmhEOEPev" class="download" target="_blank" >
              <button class="block bg-green-700 hover:bg-green-800 text-white text-sm font-semibold tracking-wide  shadow rounded cursor-pointer px-6 py-3">
              <span>My Resume</span>
          </button>
            </a>
        </div>
      </div> <!-- end get-to-know me -->
    </div>

    <div class="overflow-x-hidden">
      <div id="contact" style="position: relative; top: -40px; left: 0"/>
      <div class="contact-me bg-background-secondary pt-16">
        <div class="container-inner mx-auto text-xl pb-4 relative">
          <h2 class="font-bold mb-6">Contact me:</h2>

          <div class="absolute right-0 top-0" style="transform: translate(100%) rotate(180deg)">
            <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
          </div>

          <p class="mb-12">Feel free to reach out to me for projects.</p>
          <div class="text-lg sm:text-lg mb-16">
            <form   action="https://getform.io/f/0a9444a5-26a8-4fb7-8522-d61ae484971a" method="POST" class="mb-12">
              <div class="flex flex-wrap mb-6 -mx-4">
                  <div class="w-full md:w-1/2 mb-6 md:mb-0 px-4">
                      <label class="block mb-2 text-copy-primary" for="name">
                          Name
                      </label>

                      <input type="text" name="name" id="name" placeholder="Jon Snow" class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4" required>
                  </div>

                  <div class="w-full px-4 md:w-1/2">
                      <label class="block text-copy-primary mb-2" for="email">
                          Email Address
                      </label>

                      <input type="email" name="email" id="email" placeholder="email@example.com"  class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-green-700 mb-2 p-4"  required>
                  </div>
              </div>

              <div class="w-full mb-12">
                  <label class="block text-copy-primary mb-2" for="message">
                      Message
                  </label>

                  <textarea id="message" rows="5" name="message" class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none appearance-none focus:border-green-700 mb-2 px-4 py-4" placeholder="Enter your message here." required></textarea>
              </div>

              <div class="flex justify-end w-full">
                  <input type="submit" value="Submit" class="block bg-green-700 hover:bg-green-800 text-white text-sm font-semibold tracking-wide uppercase shadow rounded cursor-pointer px-6 py-3">
              </div>
          </form>
          </div>
        </div>
      </div> <!-- end contact-me -->
    </div>
  
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Home'
  }
}
</script>
