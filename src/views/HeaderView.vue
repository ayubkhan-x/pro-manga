<template>
  <header>
    <div class="header__big_div container df">
      <div class="header__logo__div">
        <img src="../assets/logo.png" alt="">
      </div>
      <div class="header__search__div df">
        <div class="header_search_filter df">filter</div>
        <input type="search" placeholder="Search manga..." class="header__search__input">
        <img src="../assets/images/search.png" alt="">
      </div>
      <div class="header__ul__div df">
        <li><a href="#">Completed</a></li>
        <li><a href="#">Types</a></li>
        <li><a href="#">A-Z List</a></li>
        <li><a href="#">News</a></li>
      </div>
      <div class="header__mode__div df">
        <img src="../assets/images/mode.png" alt="">
        <h3>Dark Mode</h3>
      </div>
      <div class="header__user__div df">
        <img src="../assets/images/user.png" alt="">
        <h3>Member</h3>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderView"
}
</script>

<style lang="scss">
    header {
      background: #7B36CE;
      height: 120px;

      .header__big_div {
        height: 120px;

        .header__search__div {
          background-color: #fff;
          border-radius: 9px;
          padding: 10px 15px 10px 7px;
          margin-right: 43px;
          margin-left: 29px;
          .header_search_filter {
            height: 35px;
            width: 53px;
            border-radius: 6px;
            background: #E9DAFF;
            margin-right: 12px;
            text-transform: uppercase;
            color: #5F25A6;
            font-weight: 500;
            font-size: 14px;
            justify-content: center;
          }

          .header__search__input {
            border-radius: 9px;
            border: none;
            outline: none;
            background: none;
          }
        }
        .header__ul__div {
          li {
            font-size: 18px;
            font-weight: 600;
            padding-right: 35px;
          }
        }
        .header__mode__div {
          color: #fff;
          font-size: 14px;
          font-weight: 600;
          margin-left: 65px;
          img{
             margin-right: 10px;
           }
        }
        .header__user__div {
          justify-content: center;
          color: #fff;
          font-size: 14px;
          font-weight: 600;
          margin-left: 65px;
          img{
            margin-right: 6.6px;
          }
        }
      }
    }
</style>