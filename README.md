# chapter3-UI
第三次安卓开发，做UI动画

作业1实现：
 seekBar.setMax(100);
 float  jindu=(float)progress/100;
 animationView.setProgress(jindu);

作业2实现：
// TODO 1：在这里实现另一个 ObjectAnimator，对 target 控件的大小进控件的大小进行缩放行缩放，从 1 到 2 循环ObjectAnimator animator2 = ObjectAnimator.ofFloat(target,"scaleY",1,2);

// TODO 2：在这里实现另一个 ObjectAnimator，对 target 控件的透明度进行修改，从 1 到 0.5f 循环 ObjectAnimator animator3 = ObjectAnimator.ofFloat(target,"alpha",1f,0.5f);
// TODO 3: 将上面创建的其他 ObjectAnimator 都添加到 AnimatorSet 中animatorSet = new AnimatorSet(animatorSet.playTogether(animator1,animator2,animator3);
