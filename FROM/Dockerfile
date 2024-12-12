FROM almalinux
ARG course="naveen" \
    duration="120"

RUN echo "Course: $course, Duration: $duration"  # This will show the values during build time

RUN dnf install nginx -y

CMD ["nginx", "-g", "daemon off;"]
