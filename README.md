jquery-plug-in
==============

this is jquery plug-in method


for example:

var nnfunction = nnfunction || (function($){
  var _this = {};
	
	_this.interface = interface;
	
	return _this;
})(jQuery);


var obj = {
	get:function(){
	
	},
	set:function(){
	
	},
	add:function(){
	
	}
}

(function($){
	var TTShow = function(options){
	
	};
	
	TTShow.prototype = {
		init:function(){
		
		},
		bind:function(){
		
		}
	}
	
	TTShow.defaults = {
	
	}
	
	$.fn.ttshow = function(options){
		var $this = $(this),
			data = $this.data('show'),
			options = typeof options == 'object' ? optionss ; options;
			
		if(typeof options == 'string')
		{
			var args = Array.prototype.slice.call( arguments, 1 );
			
			if(!$.isFunction(data[options]) || options.charAt(0) === "_") return;
			
			data[options]();
		}
		else if(!data)
		{
			$this.data('show',new TTshow(options));
		}
		
		return this;
	}
})(jQuery);


(function($){
	$.TT_Slideshow = function(){
		this.init();
		this.bind();
	}
	
	$.TT_Slideshow.prototype = {
		init:function(){
			this.a = '';
			this.b = '';
		},
		bind:function(){
		
		}
	}
	
	$.fn.ttshow = function(options){
		return this;
	}
	
	
})(jQuery);

