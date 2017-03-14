# DrawLineBy-CSS-or-Canvas
Lines Draw between two or multiple elments of DOM by canvas or css Raw

 By CSS 
 
    var lines = [{
        from: "here id of element1",
        to: "here id of element2"
    }];
    
    connector.drawLines(lines);
    
    
By CANVAS 

    var connectors = [{
      from: $("here id of element1"),
      to: $("here id of element2")
    }];
    
    connect(connectors);
