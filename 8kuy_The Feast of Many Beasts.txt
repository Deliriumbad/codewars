function feast(beast, dish) {
return beast.split('')[0]+beast.split('').splice(-1,1) === dish.split('')[0]+dish.split('').splice(-1,1)
}