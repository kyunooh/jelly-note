<template>
  <section class="container">
    <!--TODO header 만들기 -->
    <div class="left-side-bar">
      <div class="memo-search-wrapper">
        <input id="memo-search" type="text" placeholder="Search">
      </div>
      <ul class="memo-list">
        <li class="memo-element">
          <div class="memo-element-title">
            This is memo
          </div>
          <div class="memo-element-content">
            This is memos Content            This is memos Content Do you what I mean??
            This is memos Content Do you what I mean??
            This is memos Content Do you what I mean??
            This is memos Content Do you what I mean??
            This is memos Content Do you what I mean??
            Do you what I mean??
          </div>
        </li>
        <li class="memo-element">
          <div class="memo-element-title">
            This is memo
          </div>
          <div class="memo-element-content">
            This is memos Content Do you what I mean??
          </div>
        </li>
        <li class="memo-element">
          <div class="memo-element-title">
            This is memo
          </div>
          <div class="memo-element-content">
            This is memos Content Do you what I mean??
          </div>
        </li>
        <li class="memo-element">
          <div class="memo-element-title">
            This is memo
          </div>
          <div class="memo-element-content">
            This is memos Content Do you what I mean??
          </div>
        </li>
        <li class="memo-element">
          <div class="memo-element-title">
            This is memo
          </div>
          <div class="memo-element-content">
            This is memos Content Do you what I mean??
          </div>
        </li>

      </ul>
    </div>
    <div class="main-contents">
      Contents
    </div>
  </section>
</template>

<script>

  export default {}
</script>

<style>
  .container {
    min-height: 100vh;
    display: flex;
    flex-direction: row;
  }

  .left-side-bar {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    width: 20%;
    min-width: 180px;
    max-width: 450px;
  }

  .memo-search-wrapper {
    padding: 5px;
    margin-left: 5px;
    margin-right: auto;
    text-align: center;
  }

  #memo-search {
    width: 95%;
    min-width: 160px;
  }

  .memo-list {
    padding: 5px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: left;
    list-style: none;
    max-width: 430px;

  }

  .memo-element {
    padding: 5px;
    height: 60px;
    width: calc(100% - 20px);
    overflow: hidden;
  }

  .memo-element:hover {
    background: rgba(255, 136, 0, 0.35);
  }

  .memo-element-title {
    font-size: 1.2rem;
    font-weight: bold;
  }

  .memo-element-content {
    font-size: 0.8rem;
    width: calc(100% - 20px);

    max-width: 95%;
    color: grey;
    white-space: nowrap;
    overflow: hidden;
    word-break: break-all;
    text-overflow: ellipsis;
  }

</style>

