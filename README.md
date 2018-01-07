# topo

            var topo = new Topo.Core();
            var data = {
                centerX: 100,
                centerY: 100,
                width: 50,
                height: 50,
                label: "test",
                fontSize: 14,
                icon: "icon.png",
                fontColor: "#000000"
            };
            var node1 = topo.addNode(data);
            data.centerX = 400;
            data.centerY = 400;
            var node2 = topo.addNode(data);

            topo.addLine(data, node1, node2);
            topo.addLine(data, node1, node2);
