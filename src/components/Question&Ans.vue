<template>
  <section className="bg-[#f6fffa] px-4">
    <h1 className="font-ptserif text-center text-3xl font-semibold py-20">
      You have questions? <br />
      We have answers.
    </h1>

    <div>
      <article className="text-[#21312A]">
        <div className="flex items-center justify-between pb-4 border-b-[1px]">
          <h1 className="font-semibold font-ptserif text-lg">What is Eden?</h1>
          <button type="button" className="">
            <MinusSvg />
          </button>
          <button type="button" className="hidden"></button>
        </div>
        <p className="py-4 text-[0.91rem]">
          Easy. We're bringing the convenience of room service to homes across
          Africa - but starting with Lagos. Home tasks are routine activities
          that should be outsourced, so you can focus on the things with the
          most impact in your life. It could be making time for work that
          matters, or for enjoyment. You deserve to live well without the extra
          effort. <br />Some people call us the
          <strong> Concierge of Comfort</strong> - they're correct.
        </p>
      </article>

      <article className="text-[#21312A] my-4">
        <div className="flex items-center justify-between pb-4 border-b-[1px]">
          <h1 className="font-semibold font-ptserif text-lg">
            A laundry service, cleaning service or food service?
          </h1>

          <button type="button" className="">
            <PlusSvg />
          </button>

          <button type="button" className="hidden">
            <MinusSvg />
          </button>
        </div>
        <p className="py-4 text-[0.91rem] hidden">
          We do all three. But you get to decide which works best for you. If
          you need food, we'll get you delicious meals everyday, once a week, or
          every two weeks. Dirty laundry? We'll pick them up and bring back your
          clothes, freshly washed folded/ironed. Does your home need cleaning?
          We'll get that done efficiently as well.

          <br />

          You can even subscribe for more than one service, and we'll run it.
          Perfectly.
        </p>
      </article>

      <article className="text-[#21312A] my-4">
        <div className="flex items-center justify-between pb-4 border-b-[1px]">
          <h1 className="font-semibold font-ptserif text-lg">
            How does it work?
          </h1>

          <button type="button" className="">
            <PlusSvg />
          </button>

          <button type="button" className="hidden">
            <MinusSvg />
          </button>
        </div>

        <p className="py-4 text-[0.91rem] hidden">
          When you sign up on <a href="#" className="text-[#03a84e]">Eden</a>,
          you can configure a plan that fits your needs, then you get assigned a
          Gardener to help you manage your home. The app takes your food,
          laundry, and home cleaning needs and turns them into tasks that our
          Gardeners attend to on schedule. The only finger you'll be lifting is
          the one scrolling through the app, monitoring progress.
        </p>
      </article>

      <article className="text-[#21312A] my-4">
        <div className="flex items-center justify-between pb-4 border-b-[1px]">
          <h1 className="font-semibold font-ptserif text-lg">
            Who are Gardeners?
          </h1>

          <button type="button" className="">
            <PlusSvg />
          </button>

          <button type="button" className="hidden">
            <MinusSvg />
          </button>
        </div>

        <p className="py-4 text-[0.91rem] hidden">
          Your Home Managers. They're the human side of Eden: carefully-screened
          people (we run full background checks on all Gardeners) who are
          trained to handle your home requests with ease and enthusiasm.
          <br />
          Our Gardeners fit a profile. They're detail-oriented, responsive,
          responsible and friendly. They have one job, and that job is to
          understand what the perfect home means for you specifically, then work
          everyday to provide you with exactly that.
          <br />
          When you sign up on Eden, you see a profile of your Gardener, and you
          can get an impression of them before they start handling your chores
        </p>
      </article>

      <article className="text-[#21312A] my-4">
        <div className="flex items-center justify-between pb-4 border-b-[1px]">
          <h1 className="font-semibold font-ptserif text-lg">
            How much are they good for?
          </h1>

          <button type="button" className="">
            <PlusSvg />
          </button>

          <button type="button" className="hidden">
            <MinusSvg />
          </button>
        </div>

        <p className="py-4 text-[0.91rem] hidden">
          A lot. Think of your Gardener as your link to an ever-expanding world
          of Eden services you can take advantage of. Your Gardener helps you
          access services like<strong>
            meals, house cleaning (standard and deep cleaning), and laundry
            services.</strong
          >
          And that's just the beginning.
          <br />
          If there's ever a service you wish your Gardener provided (that they
          don't, as yet), select the 'Feedback' option on the Gardener profile,
          and we'll get the message!
        </p>
      </article>

      <article className="text-[#21312A] my-4">
        <div className="flex items-center justify-between pb-4 border-b-[1px]">
          <h1 className="font-semibold font-ptserif text-lg">
            Does my Gardener handle just my Eden account?
          </h1>

          <button type="button" className="">
            <PlusSvg />
          </button>

          <button type="button" className="hidden">
            <MinusSvg />
          </button>
        </div>

        <p className="py-4 text-[0.91rem] hidden">
          Your Gardener's schedule is designed to give the best attention to
          your chores, which gives them (based on our very trusty Eden math)
          enough time to attend to a few other customers in the same area as
          you. This means that our Gardeners attend to a handful of customers,
          but are never swamped with requests.
        </p>
      </article>
    </div>
    <Location />
  </section>
</template>

<script setup lang="ts">
import MinusSvg from "./MinusSvg.vue";
import PlusSvg from "./PlusSvg.vue";
import Location from "./Location.vue";
</script>
