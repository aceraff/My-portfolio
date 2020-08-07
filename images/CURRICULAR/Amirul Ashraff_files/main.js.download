$(document).ready(function () {
  // menu effect

  $(".menu-toggler").click(function () {
    $(".stick").toggleClass(function () {
      return $(this).is(".open, .close") ? "open close" : "open";
    });
    $(".top-nav").toggleClass("open");
  });

  $(".top-nav .nav-link").on("click", function () {
    $(".stick-1").removeClass("open");
    $(".stick-2").removeClass("open");
    $(".stick-3").removeClass("open");
    $(".top-nav").removeClass("open");
  });

  $("#up").on("click", function () {
    $("html, body").animate(
      {
        scrollTop: 0,
      },
      2000
    );
  });
});
