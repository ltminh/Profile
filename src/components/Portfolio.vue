<template>
  <section class="portfolio gray-bg has-gradient-both" id="portfolio">
        <div class="container">
            <h2 class="has-ellipsis-left">My Portfolio</h2>

            <!-- Gallery Navigation -->
            <div class="gallery text-center">
                <ul class="controls list-inline">
                    <li class="list-inline-item">
                        <div class="filter" data-filter="all">All</div>
                    </li>
                    <li class="list-inline-item">
                        <div class="filter" data-filter=".web-design">Android</div>
                    </li>
                    <li class="list-inline-item">
                        <div class="filter" data-filter=".ux-design">Xamarin</div>
                    </li>
                    <!-- <li class="list-inline-item">
                        <div class="filter" data-filter=".typography">Typography</div>
                    </li> -->
                </ul>

                <!-- Gallery Items -->
                <div id="gallery" class="row">
                    <div class="mix web-design col-lg-4 col-md-6">
                        <div class="item wow fadeInUp">
                            <a href="/static/theme/img/work-1.jpg" class="image" data-fancybox="gallery">
                                <img src="/static/theme/img/work-1.jpg" class="img-fluid" alt="...">
                                <div class="overlay hidden-sm-down d-flex justify-content-center align-items-center">
                                    <div class="icon"></div>
                                </div>
                            </a>
                        </div>
                    </div>

                    <div class="mix ux-design col-lg-4 col-md-6">
                        <div class="item wow fadeInUp" data-wow-delay="0.2s">
                            <a href="/static/theme/img/work-2.jpg" class="image" data-fancybox="gallery">
                                <img src="/static/theme/img/work-2.jpg" class="img-fluid" alt="...">
                                <div class="overlay hidden-sm-down d-flex justify-content-center align-items-center">
                                    <div class="icon"></div>
                                </div>
                            </a>
                        </div>
                    </div>

                    <div class="mix web-design col-lg-4 col-md-6">
                        <div class="item wow fadeInUp" data-wow-delay="0.4s">
                            <a href="/static/theme/img/work-3.jpg" class="image" data-fancybox="gallery">
                                <img src="/static/theme/img/work-3.jpg" class="img-fluid" alt="...">
                                <div class="overlay hidden-sm-down d-flex justify-content-center align-items-center">
                                    <div class="icon"></div>
                                </div>
                            </a>
                        </div>
                    </div>

                    <div class="mix typography col-lg-4 col-md-6">
                        <div class="item wow fadeInUp" data-wow-delay="0.6s">
                            <a href="/static/theme/img/work-4.jpg" class="image" data-fancybox="gallery">
                                <img src="/static/theme/img/work-4.jpg" class="img-fluid" alt="...">
                                <div class="overlay hidden-sm-down d-flex justify-content-center align-items-center">
                                    <div class="icon"></div>
                                </div>
                            </a>
                        </div>
                    </div>

                    <div class="mix ux-design col-lg-4 col-md-6">
                        <div class="item wow fadeInUp" data-wow-delay="0.8s">
                            <a href="/static/theme/img/work-5.jpg" class="image" data-fancybox="gallery">
                                <img src="/static/theme/img/work-5.jpg" class="img-fluid" alt="...">
                                <div class="overlay hidden-sm-down d-flex justify-content-center align-items-center">
                                    <div class="icon"></div>
                                </div>
                            </a>
                        </div>
                    </div>

                    <div class="mix web-design col-lg-4 col-md-6">
                        <div class="item wow fadeInUp" data-wow-delay="1s">
                            <a href="/static/theme/img/work-6.jpg" class="image" data-fancybox="gallery">
                                <img src="/static/theme/img/work-6.jpg" class="img-fluid" alt="...">
                                <div class="overlay hidden-sm-down d-flex justify-content-center align-items-center">
                                    <div class="icon"></div>
                                </div>
                            </a>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
  name: 'Portfolio'
}
</script>