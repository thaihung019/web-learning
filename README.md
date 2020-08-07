<<<<<<< HEAD
### create animate CSS

## create keyframe
=======
#create keyframe

>>>>>>> ef9625b25d9947011b36c27922a9d710d8e39aac
```
@keyframes bounce {
    0% {
        top: 0;
    }
    50% {
        top: -10px;
    }
    100% {
        top: 0;
    }
}

@keyframes heartBeat {
    0% {
        transform: scale(1);
    }
    30% {
        transform: scale(0.8);
    }
    60% {
        transform: scale(1.4);
    }
    100% {
        transform: scale(1);
    }
}
```

<<<<<<< HEAD
## create animate
=======
#create animate
>>>>>>> ef9625b25d9947011b36c27922a9d710d8e39aac
```
.infoSocial .fa:hover {
    animation: bounce 500ms linear infinite;
}
.infoSocial .fa.heart:hover {
    animation: heartBeat 500ms linear infinite;
}
```