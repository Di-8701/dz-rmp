# dz-rmp
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView12"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:text="MR"
        app:layout_constraintEnd_toStartOf="@+id/textView13"
        app:layout_constraintStart_toEndOf="@+id/textView11"
        tools:layout_editor_absoluteY="205dp" />

    <TextView
        android:id="@+id/textView13"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:text="M+"
        app:layout_constraintEnd_toStartOf="@+id/textView14"
        app:layout_constraintStart_toEndOf="@+id/textView12"
        tools:layout_editor_absoluteY="205dp" />

    <TextView
        android:id="@+id/textView14"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:text="M-"
        app:layout_constraintEnd_toStartOf="@+id/textView15"
        app:layout_constraintStart_toEndOf="@+id/textView13"
        tools:layout_editor_absoluteY="205dp" />

    <TextView
        android:id="@+id/textView15"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:text="MS"
        app:layout_constraintEnd_toStartOf="@+id/textView16"
        app:layout_constraintStart_toEndOf="@+id/textView14"
        tools:layout_editor_absoluteY="205dp" />

    <TextView
        android:id="@+id/textView16"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:text="M"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toEndOf="@+id/textView15"
        tools:layout_editor_absoluteY="205dp" />

    <TextView
        android:id="@+id/textView10"
        android:layout_width="match_parent"
        android:layout_height="144dp"
        android:text="TextView"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.066" />

    <Button
        android:id="@+id/button39"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="CE"
        app:layout_constraintBottom_toTopOf="@+id/button35"
        app:layout_constraintEnd_toStartOf="@+id/button15"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toEndOf="@+id/button17"
        app:layout_constraintTop_toBottomOf="@+id/textView13"
        app:layout_constraintVertical_bias="1.0" />

    <Button
        android:id="@+id/button38"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="%"
        app:layout_constraintBottom_toTopOf="@+id/button34"
        app:layout_constraintEnd_toStartOf="@+id/button16"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView12"
        app:layout_constraintVertical_bias="1.0" />

    <Button
        android:id="@+id/button41"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="⌫"
        app:layout_constraintBottom_toTopOf="@+id/button37"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toEndOf="@+id/button15"
        app:layout_constraintTop_toBottomOf="@+id/textView15"
        app:layout_constraintVertical_bias="1.0" />

    <Button
        android:id="@+id/button40"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="C"
        app:layout_constraintBottom_toTopOf="@+id/button36"
        app:layout_constraintEnd_toStartOf="@+id/button14"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toEndOf="@+id/button16"
        app:layout_constraintTop_toBottomOf="@+id/textView14"
        app:layout_constraintVertical_bias="1.0" />

    <Button
        android:id="@+id/button34"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="1/x"
        app:layout_constraintBottom_toTopOf="@+id/button30"
        app:layout_constraintEnd_toStartOf="@+id/button16"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <Button
        android:id="@+id/button36"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="2√x"
        app:layout_constraintBottom_toTopOf="@+id/button32"
        app:layout_constraintEnd_toStartOf="@+id/button14"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/button16" />

    <Button
        android:id="@+id/button37"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="÷"
        app:layout_constraintBottom_toTopOf="@+id/button33"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/button15" />

    <Button
        android:id="@+id/button35"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="x²"
        app:layout_constraintBottom_toTopOf="@+id/button31"
        app:layout_constraintEnd_toStartOf="@+id/button15"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/button17" />

    <Button
        android:id="@+id/button31"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="8"
        app:layout_constraintBottom_toTopOf="@+id/button27"
        app:layout_constraintEnd_toStartOf="@+id/button15"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/button17" />

    <Button
        android:id="@+id/button30"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="7"
        app:layout_constraintBottom_toTopOf="@+id/button26"
        app:layout_constraintEnd_toStartOf="@+id/button16"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent" />

    <Button
        android:id="@+id/button33"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="×"
        app:layout_constraintBottom_toTopOf="@+id/button29"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/button15" />

    <Button
        android:id="@+id/button32"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="9"
        app:layout_constraintBottom_toTopOf="@+id/button28"
        app:layout_constraintEnd_toStartOf="@+id/button14"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/button16" />

    <Button
        android:id="@+id/button27"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="5"
        app:layout_constraintBottom_toTopOf="@+id/button23"
        app:layout_constraintEnd_toStartOf="@+id/button15"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/button17" />

    <Button
        android:id="@+id/button26"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="4"
        app:layout_constraintBottom_toTopOf="@+id/button22"
        app:layout_constraintEnd_toStartOf="@+id/button16"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent" />

    <Button
        android:id="@+id/button29"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="-"
        app:layout_constraintBottom_toTopOf="@+id/button25"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/button15" />

    <Button
        android:id="@+id/button28"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="6"
        app:layout_constraintBottom_toTopOf="@+id/button24"
        app:layout_constraintEnd_toStartOf="@+id/button14"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toEndOf="@+id/button16" />

    <Button
        android:id="@+id/button23"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="2"
        app:layout_constraintBottom_toTopOf="@+id/button16"
        app:layout_constraintEnd_toStartOf="@+id/button15"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/button17" />

    <Button
        android:id="@+id/button22"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="1"
        app:layout_constraintBottom_toTopOf="@+id/button17"
        app:layout_constraintEnd_toStartOf="@+id/button16"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent" />

    <Button
        android:id="@+id/button25"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="+"
        app:layout_constraintBottom_toTopOf="@+id/button14"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/button15" />

    <Button
        android:id="@+id/button24"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="3"
        app:layout_constraintBottom_toTopOf="@+id/button15"
        app:layout_constraintEnd_toStartOf="@+id/button14"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/button16" />

    <Button
        android:id="@+id/button16"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="0"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toStartOf="@+id/button15"
        app:layout_constraintStart_toEndOf="@+id/button17" />

    <Button
        android:id="@+id/button17"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="+/-"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toStartOf="@+id/button16"
        app:layout_constraintStart_toStartOf="parent" />

    <Button
        android:id="@+id/button14"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text="="
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toEndOf="@+id/button15" />

    <Button
        android:id="@+id/button15"
        android:layout_width="0dp"
        android:layout_height="102dp"
        android:text=","
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toStartOf="@+id/button14"
        app:layout_constraintStart_toEndOf="@+id/button16" />

    <TextView
        android:id="@+id/textView11"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:text="MC"
        app:layout_constraintEnd_toStartOf="@+id/textView12"
        app:layout_constraintStart_toStartOf="parent"
        tools:layout_editor_absoluteY="205dp" />

</androidx.constraintlayout.widget.ConstraintLayout>
