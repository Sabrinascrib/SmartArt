<script>
  import computerGirl from "../assets/computerGirl.jpg";
  import Stars from "../assets/stars.png";
</script>

<section class="flex flex-col items-center">
  <div class="text-center bg-white text-[#37f2b4] my-8">
    <h2 class="font-bold uppercase text-2xl italic">Smart Art</h2>
  </div>
  <div class="bg-gray-100 w-full">
    <h1 class="font-bold text-center text-[50px] mt-40">
      Durch Lernen wachsen Wissen <br /> und
      <span class=" text-[#37f2b4]">Möglichkeiten.</span>
    </h1>
    <p class="text-center text-lg font-medium mt-8 italic">
      🚀Englisch - Schwedisch - Webentwicklung🚀
    </p>

    <div class="flex flex-row max-w-5xl mx-auto items-center mt-20">
      <div
        class="image p-8 bg-white rounded-xl font-bold shadow-[#37f2b4] shadow"
      >
        <img src={computerGirl} alt="" />
      </div>
      <div class="ml-28 flex flex-col max-w-md">
        <h2 class="font-bold text-2xl">Über Mich</h2>
        <p class="mt-4 font-medium">
          Hallo, ich bin Sabrina, eine 16-jährige Sprachbegeisterte und vollzeit
          Frontend Webentwicklerin aus Deutschland. Ich komme aus Schweden und
          beherrsche fließend Schwedisch und Englisch. Jetzt möchte ich meine
          Sprachkenntnisse sowie mein Wissen in Webentwicklung mit dir teilen.<br
          /> <br /> Als engagierte Webentwicklerin habe ich meine Leidenschaft zum
          Beruf gemacht. Ich freue mich darauf, dich durch die aufregende Welt der
          Sprachen und Webentwicklung zu begleiten. Gemeinsam lernen und wachsen
          steht bei mir im Fokus! Ich freue mich darauf, unsere gemeinsame Zeit zu
          verbringen.
        </p>
      </div>
    </div>

    <div class="mt-96 text-center flex flex-col items-center mb-32">
      <p class="font-medium -mt-10">Scroll nach unten</p>
      <svg
        class="text-[#37f2b4]"
        xmlns="http://www.w3.org/2000/svg"
        width="40"
        height="50"
        viewBox="0 0 1024 1024"
        ><path
          fill="currentColor"
          d="M104.704 338.752a64 64 0 0 1 90.496 0l316.8 316.8l316.8-316.8a64 64 0 0 1 90.496 90.496L557.248 791.296a64 64 0 0 1-90.496 0L104.704 429.248a64 64 0 0 1 0-90.496z"
        /></svg
      >
    </div>
  </div>
</section>

<style>
  .image {
    box-shadow: -15px 15px #37f2b4;
  }

  svg {
    animation: MoveUpDown 1s linear infinite;
    position: absolute;
  }

  @keyframes MoveUpDown {
    0%,
    100% {
      bottom: 0;
    }
    50% {
      bottom: 10px;
    }
  }
</style>
