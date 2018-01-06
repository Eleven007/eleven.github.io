function quadraticBezier( p0, p1, p2, t ) {
    var k = 1 - t;
    return k * k * p0 + 2 * ( 1 - t ) * t * p1 + t * t * p2;    // 这个方程就是二次贝赛尔曲线方程
}


