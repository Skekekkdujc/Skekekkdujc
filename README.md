
int[] colorsCRNBE = { Color.parseColor("#ffffff"), Color.parseColor("#ffffff")}; android.graphics.drawable.GradientDrawable CRNBE = new android.graphics.drawable.GradientDrawable(android.graphics.drawable.GradientDrawable.Orientation.TOP_BOTTOM, colorsCRNBE);
CRNBE.setCornerRadii(new float[]{(int)100,(int)100,(int)100,(int)100,(int)100,(int)100,(int)100,(int)100});
CRNBE.setStroke((int) 3, Color.parseColor("#000000"));linear1.setElevation((float)3);
linear1.setBackground(CRNBE);
