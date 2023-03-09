<template>
  <section className="px-4">
    <div className="bg-white p-4 rounded-md mb-10">
      <article className="">
        <figure className="flex gap-2 items-center">
          <img
            :src="arnold"
            alt="Enjoyment king"
            className="rounded-full w-16 object-cover"
          />
          <div>
            <h1>ENJOYMENT KING</h1>
            <p className="text-[#03a84e] text-sm">ArnoldOlunja</p>
          </div>
        </figure>
        <p className="text-[0.9rem] py-5 text-[#57645e]">
          My apartment was cleaned by
          <span className="text-[#03a84e]"> @ouredenlife </span>, now I have
          free time to do what matters. Get a cleaning subscription here and be
          free like me
        </p>
      </article>
      <article>
        <figure className="flex gap-2 items-center">
          <img
            :src="devfunsho"
            alt="Okubanjo Oluwafunsho"
            className="rounded-full w-16 object-cover"
          />
          <div>
            <h1>Okubanjo Oluwafunsho</h1>
            <p className="text-[#03a84e] text-sm">@devfunsho</p>
          </div>
        </figure>
        <p className="text-[0.9rem] py-5 text-[#57645e]">
          Why would i want to cancel my
          <span className="text-[#03a84e]"> @ouredenlife </span> food
          subscription nitori Olorun?! See better food na.
          <br />
          <br />
          Ofada rice, moi moi, with orishirishi assorted meat 😍
        </p>
      </article>
    </div>

    <div>
      <article className="bg-white p-4 rounded-md mb-10">
        <figure className="flex gap-2 items-center">
          <img
            :src="eno"
            alt="Osasenaga Eno"
            className="rounded-full w-16 object-cover"
          />
          <div>
            <h1>Foundational Nigerian</h1>
            <p className="text-[#03a84e] text-sm">@OsasenagaEno</p>
          </div>
        </figure>
        <p className="text-[0.9rem] py-5 text-[#57645e]">
          <span className="text-[#03a84e]"> @ouredenlife </span> has some great
          cleaners who do detailing. At one point we had to insist on a
          particular lady because of her thorough she was. She cleaned for
          months till she had to relocate.
        </p>
      </article>

      <article className="bg-white p-4 rounded-md mb-10">
        <figure className="flex gap-2 items-center">
          <img
            :src="misanxo"
            alt="misanxo"
            className="rounded-full w-16 object-cover"
          />
          <div>
            <h1>Pixie Ears</h1>
            <p className="text-[#03a84e] text-sm">@misanxo</p>
          </div>
        </figure>
        <p className="text-[0.9rem] py-5 text-[#57645e]">
          <span className="text-[#03a84e]"> @ouredenlife </span> are experts
          making food deliveries (which is an incredibly hard thing to do Ops
          wise btw) look so easy Great customer service + packaging. Love my sub
          already!
        </p>
      </article>
    </div>

    <div>
      <article className="bg-white p-4 rounded-md mb-10">
        <figure className="flex gap-2 items-center">
          <img
            :src="philip"
            alt="philip"
            className="rounded-full w-16 object-cover"
          />
          <div>
            <h1>Philip Ese</h1>
            <p className="text-[#03a84e] text-sm">@KingRohv</p>
          </div>
        </figure>
        <p className="text-[0.9rem] py-5 text-[#57645e]">
          I have to say
          <span className="text-[#03a84e]"> @ouredenlife </span> has simplified
          my life sha. Form food to laundry and house cleaning. And i have the
          best gardner. Will gladly invest if i see the opportunity.
        </p>
      </article>

      <article className="bg-white p-4 rounded-md mb-10">
        <figure className="flex gap-2 items-center">
          <img
            :src="jessica"
            alt="jessica"
            className="rounded-full w-16 object-cover"
          />
          <div>
            <h1>Creator's Art</h1>
            <p className="text-[#03a84e] text-sm">@_JessicaLouis_</p>
          </div>
        </figure>
        <p className="text-[0.9rem] py-5 text-[#57645e]">
          Laundry.
          <br />
          <br />
          Which is why i'm grateful for what
          <span className="text-[#03a84e]"> @ouredenlife </span> is doing. I
          spent all of 10 minutes yesterday putting my laundry in a bag, and i
          handed it off. I know i'll get clean, folded clothes
        </p>
      </article>
    </div>

    <div>
      <article className="bg-white p-4 rounded-md mb-10">
        <figure className="flex gap-2 items-center">
          <img
            :src="ronke"
            alt="ronke"
            className="rounded-full w-16 object-cover"
          />
          <div>
            <h1>Ronke.eth</h1>
            <p className="text-[#03a84e] text-sm">@Ronke_Kuss</p>
          </div>
        </figure>
        <p className="text-[0.9rem] py-5 text-[#57645e]">
          I'm the best in relationship with
          <span className="text-[#03a84e]"> @ouredenlife </span> and there will
          be no going back. This service is top-notch and sincerely stress
          relieving. Eden is a blessing!
        </p>
      </article>

      <article className="bg-white p-4 rounded-md">
        <figure className="flex gap-2 items-center">
          <img
            :src="joykare"
            alt="jessica"
            className="rounded-full w-16 object-cover"
          />
          <div>
            <h1>Warugu 🤯🤯</h1>
            <p className="text-[#03a84e] text-sm">@joykare_</p>
          </div>
        </figure>
        <p className="text-[0.9rem] py-5 text-[#57645e]">
          <span className="text-[#03a84e]"> @ouredenlife </span> getting my
          laundry done today and i can't rave enough about their customer
          service! I feel really loved and heard today 🥰🥰🥰 Thanks Anne cc.
          @M_Slim @nadayar @uncodeveloper and everyone else on the team
        </p>
      </article>
    </div>
  </section>
</template>

<script setup lang="ts">
import arnold from "../assets/customer-arnold.8d74292.png";
import devfunsho from "../assets/customer-devfunsho.6aa53fa.png";
import eno from "../assets/customer-eno.29b62b1.png";
import jessica from "../assets/customer-jessica.11334ac.png";
import joykare from "../assets/customer-joykare.60d52e2.png";
import misanxo from "../assets/customer-misanxo.dee3647.png";
import philip from "../assets/customer-philip.d9e8a44.png";
import ronke from "../assets/customer-ronke.f39f9cb.png";
</script>
