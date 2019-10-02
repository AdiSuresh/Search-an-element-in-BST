boolean search(node r, int val) {
	if(r == null)
		return false;
	if(val > r.data){
		if(r.right != null)
			return search(r.right,val);
	}
	else if(val < r.data){
		if(r.left != null)
			return search(r.left,val);
	}
	else
		return true;
	return false;
  }
