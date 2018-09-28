<template>
  <div class="container">

    <div class="border p-3">
      <div class="d-flex p-2 bg-primary">I'm a flexbox container!</div>
    </div>
    <div class="border p-3">
      <pre><code class="language-html" data-lang="html"><span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"d-flex p-2 bg-primary"</span><span class="nt">&gt;</span>I'm a flexbox container!<span class="nt">&lt;/div&gt;</span></code></pre>
    </div>
    <div class="border p-3">
      <div class="d-inline-flex p-2 bg-primary">I'm an inline flexbox container!</div>
    </div>
    <div class="border p-3">
      <pre>
        <code class="language-html" data-lang="html">
          <span class="nt">&lt;div</span> <span class="na">class=</span><span class="s">"d-inline-flex p-2 bg-primary"</span><span class="nt">&gt;</span>I'm an inline flexbox container!<span class="nt">&lt;/div&gt;</span>
        </code>
      </pre>
    </div>
  </div>
</template>

<script>
export default {
  name: 'EnableFlexBehaviors',
};
</script>

<style>
pre {
  padding-bottom: 0;
}
.nt {
    color: #2f6f9f;
}
.na {
    color: #4f9fcf;
}
.s {
    color: #d44950;
}
</style>
