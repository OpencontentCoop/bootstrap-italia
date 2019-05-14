---
layout: docs
title: Schede
description: Un altro contenitore di contenuti con molte opzioni e varianti.
group: componenti
toc: true
---

Le **schede** sono contenitori flessibili ed estendibili.

Di default le schede si estendono completamente al 100% del loro elemento contenitore.

Negli esempi seguenti le schede sono all'interno di una struttura colonnare di bootstrap.  
L'inizio della scheda vera e propria è segnalata dal commento `start scheda`

## Utilizzo

{% capture example %}
<div class="row">
  <div class="col-12 col-lg-5">
    <!--start scheda-->
    <div class="scheda">
      <div class="scheda-icon">
        <a href="#">
          <svg class="icon">
              <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-settings"></use>
          </svg>
          <span>Aenean ipsum ante</span>
        </a>
      </div>
      <div class="scheda-text">
          <h4><a href="#">Lorem ipsum</a></h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean ipsum ante, imperdiet ut turpis non, egestas fringilla erat. Mauris vitae lorem elit. Etiam et vestibulum leo. Morbi feugiat vitae nulla nec aliquet. Vivamus pellentesque orci sed egestas vulputate. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec in dapibus urna. Nulla at euismod nulla. Fusce tincidunt eget ex et elementum. </p>
      </div>
      <div class="scheda-footer">
          <a href="#" class="read-more">
              Lorem ipsum dolor
              <svg class="icon">
                  <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-arrow-right"></use>
              </svg>
          </a>
      </div>      
    </div>
    <!--end card-->
  </div>
</div>
{% endcapture %}{% include example.html content=example %}

## Variante small 

{% capture example %}
<div class="row">
  <div class="col-12 col-lg-5">
    <!--start scheda-->
    <div class="scheda scheda-sm">
      <div class="scheda-icon">
        <a href="#">
          <svg class="icon">
              <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-settings"></use>
          </svg>
          <span>Aenean ipsum ante</span>
        </a>
      </div>
      <div class="scheda-text">
          <h4><a href="#">Lorem ipsum</a></h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean ipsum ante, imperdiet ut turpis non, egestas fringilla erat. Mauris vitae lorem elit. Etiam et vestibulum leo. Morbi feugiat vitae nulla nec aliquet. Vivamus pellentesque orci sed egestas vulputate. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec in dapibus urna. Nulla at euismod nulla. Fusce tincidunt eget ex et elementum. </p>
      </div>
      <div class="scheda-footer">
          <a href="#" class="read-more">
              Lorem ipsum dolor
              <svg class="icon">
                  <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-arrow-right"></use>
              </svg>
          </a>
      </div>      
    </div>
    <!--end card-->
  </div>
</div>
{% endcapture %}{% include example.html content=example %}

## Ombreggiatura e angoli arrotondati

{% capture example %}
<div class="row">
  <div class="col-12 col-lg-5">
    <!--start scheda-->
    <div class="scheda scheda-shadow">
      <div class="scheda-icon">
        <a href="#">
          <svg class="icon">
              <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-settings"></use>
          </svg>
          <span>Aenean ipsum ante</span>
        </a>
      </div>
      <div class="scheda-text">
          <h4><a href="#">Lorem ipsum</a></h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean ipsum ante, imperdiet ut turpis non, egestas fringilla erat.</p>
      </div>
      <div class="scheda-footer">
          <a href="#" class="read-more">
              Lorem ipsum dolor
              <svg class="icon">
                  <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-arrow-right"></use>
              </svg>
          </a>
      </div>      
    </div>
    <!--end card-->
  </div>
  <div class="col-12 col-lg-5 offset-lg-2">
    <!--start scheda-->
    <div class="scheda scheda-sm scheda-round scheda-shadow">
      <div class="scheda-icon">
        <a href="#">
          <svg class="icon">
              <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-settings"></use>
          </svg>
          <span>Aenean ipsum ante</span>
        </a>
      </div>
      <div class="scheda-text">
          <h4><a href="#">Lorem ipsum</a></h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean ipsum ante, imperdiet ut turpis non, egestas fringilla erat.</p>
      </div>
      <div class="scheda-footer">
          <a href="#" class="read-more">
              Lorem ipsum dolor
              <svg class="icon">
                  <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-arrow-right"></use>
              </svg>
          </a>
      </div>      
    </div>
    <!--end card-->
  </div>
</div>
{% endcapture %}{% include example.html content=example %}

## Variante banner 

{% capture example %}
<div class="row">
  <div class="col-12 col-lg-5">
    <!--start scheda-->
    <div class="scheda scheda-banner">
      <div class="scheda-icon">
        <a href="#">
          <svg class="icon">
              <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-settings"></use>
          </svg>
          <span>Aenean ipsum ante</span>
        </a>
      </div>
      <div class="scheda-text">
          <h4><a href="#">Lorem ipsum</a></h4>
          <p>Lorem ipsum dolor sit ametconsectetur adipiscing elit. Aenean ipsum ante.</p>
      </div>
      <div class="scheda-footer">
          <a href="#" class="read-more">
              Lorem ipsum dolor
              <svg class="icon">
                  <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-arrow-right"></use>
              </svg>
          </a>
      </div>      
    </div>
    <!--end card-->
  </div>
  <div class="col-12 col-lg-5 offset-lg-2">
    <!--start scheda-->
    <div class="scheda scheda-banner scheda-shadow">
      <div class="scheda-icon">
        <a href="#">
          <svg class="icon">
              <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-settings"></use>
          </svg>
          <span>Aenean ipsum ante</span>
        </a>
      </div>
      <div class="scheda-text">          
          <p><b>LOREM IPSUM</b><br />dolor sit ametconsectetur adipiscing elit.</p>
      </div>      
    </div>
    <!--end card-->
  </div>
</div>
{% endcapture %}{% include example.html content=example %}

## Varianti di colore

{% capture example %}
<div class="row">
  <div class="col-12 col-lg-5">
    <!--start scheda-->
    <div class="scheda primary-bg white-color primary-border-color">
      <div class="scheda-icon">
        <a href="#">
          <svg class="icon">
              <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-settings"></use>
          </svg>
          <span>Aenean ipsum ante</span>
        </a>
      </div>
      <div class="scheda-text">
          <h4><a class="white-color" href="#">Lorem ipsum</a></h4>
          <p>Lorem ipsum dolor sit ametconsectetur adipiscing elit. Aenean ipsum ante.</p>
      </div>
      <div class="scheda-footer white-bg">
          <a href="#" class="read-more">
              Lorem ipsum dolor
              <svg class="icon">
                  <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-arrow-right"></use>
              </svg>
          </a>
      </div>      
    </div>
    <!--end card-->
    <!--start scheda-->
    <div class="scheda scheda-sm border-warning">
      <div class="scheda-icon">
        <a href="#" class="text-warning">
          <svg class="icon icon-warning">
              <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-settings"></use>
          </svg>
          <span>Aenean ipsum ante</span>
        </a>
      </div>
      <div class="scheda-text">
          <h4 class="text-warning"><a  class="text-warning" href="#">Lorem ipsum</a></h4>
          <p>Lorem ipsum dolor sit ametconsectetur adipiscing elit. Aenean ipsum ante.</p>
      </div>
      <div class="scheda-footer">
          <a href="#" class="read-more">
              Lorem ipsum dolor
              <svg class="icon">
                  <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-arrow-right"></use>
              </svg>
          </a>
      </div>      
    </div>
    <!--end card-->
  </div>
  <div class="col-12 col-lg-5 offset-lg-2">
    <!--start scheda-->
    <div class="scheda scheda-banner primary-border-color white-bg">
      <div class="scheda-icon primary-color">
        <a href="#">
          <svg class="icon icon-primary">
              <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-settings"></use>
          </svg>
          <span>Aenean ipsum ante</span>
        </a>
      </div>
      <div class="scheda-text primary-color">          
          <p><b>LOREM IPSUM</b><br />dolor sit ametconsectetur adipiscing elit.</p>
      </div>      
    </div>
    <!--end card-->
    <!--start scheda-->
    <div class="scheda scheda-banner scheda-shadow complementary-2-bg">
      <div class="scheda-icon">
        <a href="#">
          <svg class="icon icon-white">
              <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-settings"></use>
          </svg>
          <span>Aenean ipsum ante</span>
        </a>
      </div>
      <div class="scheda-text text-white">          
          <p><b>LOREM IPSUM</b><br />dolor sit ametconsectetur adipiscing elit.</p>
      </div>      
    </div>
    <!--end card-->
    <!--start scheda-->
    <div class="scheda scheda-banner scheda-shadow bg-danger">
      <div class="scheda-icon">
        <a href="#">
          <svg class="icon icon-white">
              <use xlink:href="{{ site.baseurl }}/dist/svg/sprite.svg#it-settings"></use>
          </svg>
          <span>Aenean ipsum ante</span>
        </a>
      </div>
      <div class="scheda-text text-white">          
          <p><b>LOREM IPSUM</b><br />dolor sit ametconsectetur adipiscing elit.</p>
      </div>      
    </div>
    <!--end card-->
  </div>
</div>
{% endcapture %}{% include example.html content=example %}
