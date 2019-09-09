---
title: Style Guide
subtitle: The style guide provides you with a blueprint of default post and page styles.
  The style guide is also a great reference for suggested typographic treatment and
  styles for your content.
layout: page
img_path: ''
menu:
  main:
    title: Coverage Map
    weight: 4

---
// Add source for admin-0 Boundaries

  map.addSource('admin-0', {

    type: 'vector',

    url: 'mapbox://mapbox.enterprise-boundaries-a0-v2'

  });

  // Add a layer with boundary lines

  map.addLayer({

    id: 'admin-0-line',

    type: 'line',

    source: 'admin-0',

    'source-layer': 'boundaries_admin_0',

    paint: {

      'line-color': 'red',

      'line-width': \['interpolate', \['linear'\], \['zoom'\], 0, 2, 20, 10\]

    }

  }, 'waterway-label');

  // Add a layer with points

  map.addLayer({

    id: 'admin-0-circle',

    type: 'circle',

    source: 'admin-0',

    'source-layer': 'points_admin_0',

    paint: {

      'circle-color': 'white',

      'circle-stroke-color': 'black',

      'circle-stroke-width': \['interpolate', \['linear'\], \['zoom'\], 0, 2, 20, 6\],

      'circle-radius': \['interpolate', \['linear'\], \['zoom'\], 0, 2, 20, 20\]

    }

  }, 'waterway-label');

});