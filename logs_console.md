'''
docker compose up -d

% docker build -f Dockerfile.dev .
...
=> => writing image sha256:3d36df8b7d3b2105c41c376003ad36f619e8c84128ced34dd4c16651fffeb1dd

% docker build -f Dockerfile.dev -t vbgrapp:one .
...
=> => writing image sha256:2f81efad30207c7ed2a89e0384f0e3184f499e584d8e7188b3cafba8ffe761f5
 => => naming to docker.io/library/vbgrapp:one

docker build .     --> Dockerfile will be used during this operation
'''