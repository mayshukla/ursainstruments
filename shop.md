---
layout: default
title: Shop - Ursa Instruments
---

## Shop

Check back later as I add more items!

<div class="shop-items">
    {% for item in site.data.shop-items %}
    <div class="shop-item">
        <img alt="{{ item.name }}" src="{{ item.image }}"/>
        <p class="item-name">{{ item.name }}</p>
        <p class="item-desc">{{ item.description }}</p>
    </div>
    {% endfor %}
</div>