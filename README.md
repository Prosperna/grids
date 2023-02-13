# Grids layout

## Basic grids layout

```html
<section class="my-3 $variables">
  # this is the main wrapper of the grid
  <div class="container $variables">
    #container is the wrapper of the rows there are 2 options here [:container,
    :container-fluid]
    <div class="row $variables">
      # Row a wrapper of the columns
      <div class="col $variables">
        #columns is the basic wrapper of the modules there are max columns of 12
        but we only use up 6 columns [:col-2, col-3, col-4, col-5, col-6]
        <h3 class="text $variables">Grid 1</h3>
        # modules
      </div>
    </div>
  </div>
</section>
```
