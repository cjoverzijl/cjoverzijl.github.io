<!-- Contact Section -->

If you want to get in touch, give one of these a shot.

[{{ site.email }}](mailto:{{ site.email }})
<div>
<ul class="list-inline banner-social-buttons">
    {% for network in site.social %}
    <li>
        <a href="{{ network.url }}" class="btn btn-default btn-social"><i class="fa fa-{{ network.title }} fa-fw"></i> <span class="network-name">{{ network.title }}</span></a>
    </li>
    {% endfor %}
</ul>
</div>
